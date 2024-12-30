<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import Navbar from './components/Navbar.vue'

</script>


<style>
    @font-face {
        font-family: 'Dela Gothic One';
        src: url('/src/assets/font/DelaGothicOne-Regular.ttf') format('truetype');

        font-family: 'NotoSansTC';
        src: url('/src/assets/font/NotoSansTC-VariableFont_wght') format('truetype');
    }


    @media screen {
        
    }
</style>

<template>
    <Navbar/>
    <div class="wrapper">
    </div>

</template>
