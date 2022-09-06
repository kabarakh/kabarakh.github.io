<template>
  <div class="page">
    <header class="container">
      <router-link to="/">
        <img alt="Banner for Kabarakh" class="banner" src="@/assets/banner.jpg"/>
      </router-link>

      <div id="nav">
        <router-link to="/">Home</router-link>
        <router-link to="/projects">My projects</router-link>
        <router-link to="/technologies">Technolgies</router-link>
        <!--<router-link to="/tools">Some tools</router-link>-->
      </div>
    </header>

    <main class="container">
      <slot/>
    </main>

    <footer class="container">
      <div id="nav">
        <router-link to="/imprint">Imprint</router-link>
      </div>
    </footer>
  </div>
</template>

<script setup lang="ts">
import '@/assets/Main.scss';
</script>
