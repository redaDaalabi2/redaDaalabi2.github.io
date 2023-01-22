<template>
    <nav class="">
        <img src="../assets/logo.png" alt="logo">
        <div class="mainmenu" @click="showMenu">
            <div></div>
            <div></div>
            <div></div>
        </div>
        <ul class="navbar" id="navbarId">
            <li>
                <router-link class="routenav" to="/">MWC</router-link>
            </li>
            <li>
                <router-link class="routenav" to="/service">Nos services</router-link>
            </li>
            <li>
                <router-link class="routenav" to="/reference">Nos réference</router-link>
            </li>
            <li>
                <router-link class="routenav" to="/contact">Contact</router-link>
            </li>
        </ul>
    </nav>
</template>

<script>
export default {
    name: "Nav-bar",
    data() {
        return {
            
        };
    },
    methods: {
        showMenu(){
            document.getElementById("navbarId").classList.toggle("active")
        }
    }
}
</script>

<style lang="scss">
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    padding: 0px 2rem !important;
    background-color: white;
    z-index: 999;
    top: 50;
    width: 100%;
    box-shadow: 0 0 10px #ddd;
    img {
      width: 6rem;
    }
.navbar {
        display: flex ;
        @media (max-width: 900px){
            display: none;
        }
        .routenav {
            text-decoration: none;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 60px;
            position: relative;
            color: black;
            padding: 0 30px;
            transition: 0.3s;
            overflow: hidden;
            margin-right: 10px;
            &::before {
                content: " ";
                position: absolute;
                width: 100%;
                height: 4px;
                background-color: #5AE4A8;
                top: 0;
                left: -100%;
                transition: 0.3s;
            }
            &:hover {
                color: #5AE4A8;
                background-color: white;
                font-weight: 500;
            }
            &:hover::before {
                left: 0;
            }
            @media (max-width: 900px) {
                margin-block: 10px;
                margin-right: 0px;
            }
        }
        .registernav {
            background-color: #5AE4A8;
            border-radius: 5px;
            margin-right: 10px;
            @media (max-width: 900px) {
                margin-block: 10px;
                margin-right: 0px;
                padding-inline: 28px;
            } 
        }
        .loginnav {
            background-color: #5AE4A8;
            border-radius: 5px;
            @media (max-width: 900px) {
                padding-inline: 38px;
            } 
        }
    }
}
.mainmenu div{
    width: 45px;
    height: 5px;
    background-color: black;
    margin-block: 8px;
    display: none;
    @media (max-width: 900px){
        display: block;
        cursor: pointer;
    }
}
.active{
    display: flex !important;
    align-items: center;
    flex-direction: column;
    width: 100%;
    z-index: 1111;
}
</style>