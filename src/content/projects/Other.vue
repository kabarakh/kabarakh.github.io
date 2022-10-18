<script setup lang="ts">
import TwoCol from '~/components/two-col.vue';
</script>

<template>
  <section>
    <h2>Other work (e.g. for punkt.de)</h2>
    <two-col mode="75-25">
      <template v-slot:left>
        <h3>Codeception packages</h3>
        <p>At work, we tend do write automatic behaviour/frontend tests with codeception, and we
          like to use the Gherkin syntax to be forced to write easy understandable steps for complex
          tests.</p>
        <p>When we started using this, we put the necessary steps within the test project, but that
          way we couldn't reuse them (other than copying, which would mean we lose newer developments
          in older projects). So I did what every open source dev does and created repositories for
          different codeception modules which extend them and implements gherkin steps.</p>
      </template>
      <template v-slot:right>
        <h3>Website</h3>
        <p>Because there are many packages, so let's just do the
          <a href="https://github.com/orgs/punktDe/repositories?q=codeception&type=all&language=&sort="
             target="_blank">link to the repo search
          </a>.
        </p>
      </template>
    </two-col>
    <h3>Others</h3>
    <p>Other than that, I help working on different open source packages and extensions for customer projects.
      You can check out the repo list of
      <a href="https://github.com/orgs/punktDe/repositories" target="_blank">punktDe</a>
      and <a href="https://github.com/orgs/punktDeForks/repositories" target="_blank">punktDeForks</a> to check out
      some of those.
    </p>
  </section>
</template>
