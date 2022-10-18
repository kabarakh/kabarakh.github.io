<script setup lang="ts">
import TwoCol from '~/components/two-col.vue';
</script>

<template>
  <section>
    <h2>LADXR Spoiler Log Interface</h2>
    <two-col mode="75-25">
      <template v-slot:left>
        <h3>What is this?</h3>
        <p>So you might have heard of game randomizers. And you might have heard of Legend of Zelda Link's
          Awakening.</p>
        <p>If both, you might want to check out LADXR, a randomizer for Link's Awakening.</p>
        <p>When you create a ROM, you can also create a spoiler log. This can be in JSON - and this JSON can be read
          by the LADXR Spoiler Interface!</p>
      </template>
      <template v-slot:right>
        <h3>Website</h3>
        <p>There is an online version available:
          <router-link target="_blank" to="/ladxr-spoiler-interface/">LADXR Spoiler Log Interface</router-link>
        </p>
      </template>
    </two-col>
  </section>
</template>
