<template>
  <div class="home">
    <Accueil />
  </div>
</template>

<script>
// @ is an alias to /src
import Accueil from '@/components/Accueil.vue'

export default {
  name: 'HomeView',
  components: {
    Accueil
  }
}
</script>
