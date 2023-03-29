<script setup>
import {RouterLink, RouterView} from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import Login from "@/components/Login.vue";
import Navbar from "@/components/Navbar.vue";
</script>

<template>
    <header>
        <!--    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />-->

        <Navbar/>

        <div class="wrapper">
            <!--      <HelloWorld msg="You did it!" />-->

            <!--      <nav>-->
            <!--        <RouterLink to="/">Home</RouterLink>-->
            <!--        <RouterLink to="/about">About</RouterLink>-->
            <!--      </nav>-->
        </div>
    </header>

    <RouterView/>

    <div class="footer container w-50 d-flex align-items-center mt-5 ">
        <div class="container-fluid w-50">
            <span class="fw-bold">Номер: </span><span>8 800 555 35 35</span>
        </div>

        <div class="container-fluid d-flex justify-content-center  mt-2 flex-column w-50">
            <a class="nav-link active" aria-current="page" href="#">Главная</a>
            <a class="nav-link" href="#">Акции</a>
            <a class="nav-link" href="#">Специалисты</a>
            <a class="nav-link disabled">Личный кабинет</a>
        </div>
    </div>

</template>

<style scoped>

</style>
