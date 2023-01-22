<template>
<div class="relative">
    <si-app-loader placement="BEFORE_TOP_HEADER"/>
    <div class="h-2 padding-div">
      <div class="wrapper-content">
        <a href="" class="announcement-bar__link focus-inset">
          <span class="announcement-bar__message text-center uppercase">
            <messagetop v-for="M in 40"/>
          </span>
        </a>
      </div>
    </div>
    <div class=" sticky top-0 left-0 right-0">
        <si-app-loader :placement="'BEFORE_TOP_HEADER_STICKY'"/>
    </div>
    <si-app-loader placement="AFTER_TOP_HEADER"/>
</div>
</template>

<script>
import messagetop from '@/components/messagetop.vue'
export default {
  name: 'HomeView',
  components: {
    messagetop
  }
}
</script>

<style>
.announcement-bar__message {
  color: #ffffff;
  display: inline-block;
  vertical-align: top;
  white-space: nowrap;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  width: 100%;
  animation: slide 60s linear infinite;
}
@keyframes slide {
  0% {
    transform: translate3d(0, 0, 0);
  }
  100% {
    transform: translate3d(-1500px, 0, 0); /* The image width */
  }
}
.wrapper-content {
  background: transparent;
  width: 100%;
  overflow: hidden;
  gap: 10px;
  max-height: 40px !important;
}
.announcement-bar__link link {
  display: inline-block;
  vertical-align: top;
  white-space: nowrap;
  width: 100%;
  outline: none;
  box-shadow: none;
}
.padding-div {
  padding-top: 0.5rem;
  padding-bottom: 2.5rem;
  background-color: black;
}
</style>
