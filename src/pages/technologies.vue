<script setup lang="ts">
import Layout from '~/layouts/Default.vue';
import Php from '../content/technologies/Php.vue';
import TsJs from '../content/technologies/TsJs.vue';
</script>

<script lang="ts">
export default {
  metaInfo: {
    title: 'Technologies'
  }
};
</script>

<template>
  <Layout>
    <h1>Technologies I use</h1>
    <p>... and I like to mention or explain. Thing is, that I am oftentimes the guy at work who just jumps into any
      bug and who tries to find out what the problem is, no matter the technology it's in. So I get to know a quite
      high amount of them, and after a not so long time they usually feel quite good to use.</p>
    <h2>Languages</h2>
    <Php />
    <TsJs />
    <h2>Frontend-Libraries and -Frameworks</h2>
    <p>That's a big list, but - ever since a co-worker told me "Herbie, we should do a frontend app for this thing
      the client needs, and I think you should check out Angular.js for that" - and after everything worked out quite
      well and after I noticed that I enjoy doing FE stuff - I tried to do more and more frontend and learn more and
      more technologies. We still do not enough at work and use a quite high amount of BE code, but the trend is
      pointing towards these things here.</p>
    <h3>Vue</h3>
    <h3>React</h3>
    <h3>Angular</h3>
    <h3>Svelte</h3>
    <h2>Server-Technologies</h2>
    <h3>TYPO3</h3>
    <h3>Neos</h3>
    <h3>NestJS</h3>
    <h2>Somewhere inbetween</h2>
    <h3>Gridsome</h3>
  </Layout>
</template>
