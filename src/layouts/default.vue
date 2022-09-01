<template>
  <header class="container">
    <img alt="Banner for Kabarakh" class="banner" src="@/assets/banner.jpg" />

      <div id="nav">
        <router-link to="/">Home</router-link>
        <router-link to="/projects">My projects</router-link>
        <router-link to="/technologies">Technolgies</router-link>
        <router-link to="/tools">Some tools</router-link>
      </div>
  </header>

  <slot />

  <footer>
    <div id="nav">
      <router-link to="/imprint">Imprint</router-link>
    </div>
  </footer>
</template>

<script setup lang="ts">
import "@/assets/Main.scss";
</script>
