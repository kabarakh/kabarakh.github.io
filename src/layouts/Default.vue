<template>
  <div id="top" class="page">
    <header class="container">
      <router-link to="/">
        <img alt="Banner for Kabarakh" class="banner" src="@/assets/banner.jpg"/>
      </router-link>

      <div class="nav">
        <g-link to="/">Home</g-link>
        <g-link to="/projects/">My projects</g-link>
        <g-link to="/technologies/">Technolgies</g-link>
        <!--<g-link to="/tools/">Some tools</router-link>-->
      </div>
    </header>

    <main class="container">
      <slot/>
    </main>

    <footer class="container">
      <div class="nav">
        <g-link to="/imprint/">Imprint</g-link>
      </div>
    </footer>
  </div>
</template>

<script setup lang="ts">
import '@/assets/Main.scss';
</script>
