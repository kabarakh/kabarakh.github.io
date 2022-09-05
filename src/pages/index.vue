<script setup lang="ts">
import Layout from '~/layouts/Default.vue';
import TwoCol from '~/components/two-col.vue';
</script>

<script lang="ts">
export default {
  metaInfo: {
    title: 'About me'
  }
}
</script>

<template>
  <Layout>
    <h1>Welcome to my small github overview page</h1>
    <h2>About me</h2>
    <two-col mode="75-25">
      <template v-slot:left>
        <p>The name's Kabarakh. Or Herbie. Or Christian.</p>
        <p>I've been a "real" developer since 2009. Before that, I did some scripting for mIRC and tried
          to figure out how real programming with data storage and structure really works. Then I got my abitur
          and learned to be a glorious "Fachinformatiker Anwendungsentwicklung" - which is a mouthful for "I know
          how to do this, but I don't have a diploma or similar".</p>
        <p>Web technologies are what really is my bread and butter - I often tell people that when I try out
          something new and I read the docs and try it in a small project, that it immediately feels as if I were
          within my comfort zone.</p>
        <h2>punkt.de</h2>
        <p>Since 2011 I've been working at punkt.de in Karlsruhe. We were a TYPO3 agency, but in the meantime it's
          more like "you like web? Let's do it!"</p>
        <p>We do all kinds of projects. Personally I was caught up in a project since 2012, which was fine because
          we got to try out new things, but also was bad because I had to keep developing for Internet Explorer 11...
        </p>
        <p>In the meantime I am working on other, newer projects including headless CMS, modern CSS layouts and other
          cool stuff.</p>
      </template>
      <template v-slot:right>
        <img alt="Picture of Kabarakh during a presentation" src="@/assets/me_talk.png"/>
      </template>
    </two-col>
  </Layout>
</template>

<style lang="scss" scoped>
img {
  width: 90%;
  margin: 1.5rem auto;
  max-width: 350px;
}
</style>
