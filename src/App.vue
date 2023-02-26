<script setup>
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <header>
    <img src="https://c4.wallpaperflare.com/wallpaper/410/59/609/rick-and-morty-tv-rick-sanchez-morty-smith-wallpaper-preview.jpg"/>

    <div class="wrapper">
      <HelloWorld msg="Personajes de Rick & Morty" />

      <nav>
        <RouterLink  to="/personajes">Personajes</RouterLink>
        <RouterLink  to="/about">Acerca de</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style>
</style>
