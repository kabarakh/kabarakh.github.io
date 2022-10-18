<script setup lang="ts">
import Layout from '~/layouts/Default.vue';
import TwoCol from '~/components/two-col.vue';
import LADXRSpoiler from '../content/projects/LADXRSpoiler.vue';
import DiceRoller from '../content/projects/DiceRoller.vue';
import InitiativeTool from '../content/projects/InitiativeTool.vue';
import Other from '../content/projects/Other.vue';
</script>

<script lang="ts">
export default {
  metaInfo: {
    title: 'My Projects'
  }
};
</script>

<template>
  <Layout>
    <h1>(Some of) My projects on github</h1>
    <p>The repositories can all be found at my <a target="_blank" href="https://github.com/kabarakh?tab=repositories">github
      repo list</a>
    </p>
    <LADXRSpoiler />
    <DiceRoller />
    <InitiativeTool />
    <Other />
  </Layout>
</template>
