<script setup lang="ts">
import TwoCol from '~/components/two-col.vue';
</script>

<template>
  <section>
    <h2>Dice Rollers</h2>
    <two-col mode="75-25">
      <template v-slot:left>
        <h3>What is this?</h3>
        <p>In the rules of tabletop games, dice rolls follow a specific notation. What I wanted to do was to take this
          notation (even in complicated cases), parse the input and use RNG to "roll" the dice. That way, I could keep
          my big dice bag at home while playing D&D - because I had the laptop on the table already because I didn't
          want to use paper based charsheets and stuff like that.</p>
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
</template>
