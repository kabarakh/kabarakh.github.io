<script setup lang="ts">
import Layout from '~/layouts/Default.vue';
import TwoCol from '~/components/two-col.vue';
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
    <section>
      <h1>(Some of) My projects on github</h1>
      <p>The repositories can all be found at my <a target="_blank" href="https://github.com/kabarakh?tab=repositories">github
        repo list</a>
      </p>
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

    <section>
      <h2>Dice Rollers</h2>
      <two-col mode="75-25">
        <template v-slot:left>
          <h3>What is this?</h3>
          <p>In the rules of tabletop games, dice rolls follow a specific notation. What I wanted to do was to take this
            notation (even in complicated cases), parse the input and use RNG to "roll" the dice. That way, I could keep
            my big
            dice bag at home while playing D&D - because I had the laptop on the table already because I didn't want to
            use paper based
            charsheets and stuff like that.</p>
          <p>The first version was built in AngularJS, then an Angular (2+) version followed. Since then, building a
            dice roller is often my "hello world" for a new frontend technology. The most current ready one is built in
            Vue.</p>
        </template>
        <template v-slot:right>
          <h3>Website</h3>
          <ul>
            <li>AngularJS: Doesn't exist anymore, because AngularJS is a dead technology.</li>
            <li>
              Angular:
              <router-link target="_blank" to="/diceRollerV2/">DiceRollerV2</router-link>
            </li>
            <li>
              Vue:
              <router-link target="_blank" to="/diceRollerVue/">DiceRollerVue</router-link>
            </li>
            <li>
              Svelte: Not usable. Very much not usable at the moment. The dice roller, not Svelte :D
            </li>
            <li>
              React: I thought I had a react version, but there is no repository. But there will be a version!
            </li>
          </ul>
        </template>
      </two-col>
    </section>

    <section>
      <h2>D&D Initiative Tool</h2>
      <two-col mode="75-25">
        <template v-slot:left>
          <h3>What is this?</h3>
          <p>Another thing for my D&D playing and dungeon mastering. When duing combat,
            the participants are put in order by their initiative and act in order. And there
            are possibilities to change the order. I was too lazy to think about some way
            to keep track of everything on paper, and also the players need to see the initative.</p>
          <p>The idea is to have this initiative tracker. And maybe have some kind of websocket
            connection for players with mobiles/laptops (TODO: Develop)</p>
          <p>And for the vue edition I try to build a DM helper version which keeps track of the
            characters in groups (with dates we are playing) and some of their stats. And notes for
            the monsters. And maybe an integration with the dice roller. But I keep doing too complex
            stuff and fail building a working tool...</p>
        </template>
        <template v-slot:right>
          <h3>Website</h3>
          <ul>
            <li>React:
              <router-link to="/initiative-react/" target="_blank">Initiative React</router-link>
            </li>
            <li>
              Vue: Not ready to be shown yet.
            </li>
          </ul>
        </template>
      </two-col>
    </section>

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
            </a>
            .
          </p>
        </template>
      </two-col>
      <h3>Others</h3>
      <p>Other than that, I help working on different open source packages and extensions for customer projects.
        You can check out the repo list of
        <a href="https://github.com/orgs/punktDe/repositories" target="_blank">punktDe</a>
        and <a href="https://github.com/orgs/punktDeForks/repositories" target="_blank">punktDeForks</a> to check out
        some
        of those.
      </p>

    </section>
  </Layout>
</template>
