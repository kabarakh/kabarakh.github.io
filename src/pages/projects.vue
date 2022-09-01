<template>
  <h1>(Some of) My projects on github</h1>
  <p>The repositories can all be found at my <a target="_blank" href="https://github.com/kabarakh?tab=repositories">github
    repo list</a>
  </p>
  <h2>LADXR Spoiler Log Interface</h2>
  <h3>What is this?</h3>
  <p>So you might have heard of game randomizers. And you might have heard of Legend of Zelda Link's Awakening.</p>
  <p>If both, you might want to check out LADXR, a randomizer for Link's Awakening.</p>
  <p>When you create a ROM, you can also create a spoiler log. This can be in JSON - and this JSON can be read by LADXR
    Spoiler Interface!</p>
  <h3>Website</h3>
  <p>There is an online version available:
    <router-link target="_blank" to="/ladxr-spoiler-interface/">/ladxr-spoiler-interface/</router-link>
  </p>
  <h2>Dice Rollers</h2>
  <h3>What is this?</h3>
  <p>In the rules of tabletop games, dice rolls follow a specific notation. What I wanted to do was to take this
    notation
    (even in complicated cases), parse the input and use RNG to "roll" the dice. That way, I could keep my big dice bag
    at home while playing D&D - because I had the laptop on the table already because I didn't want to use paper based
    charsheets and stuff like that.</p>
  <p>The first version was built in AngularJS, then an Angular (2+) version followed. Since then, building a dice roller
    is often my "hello world" for a new frontend technology. The most current ready one is built in Vue.</p>
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
  <h2>D&D Initiative Tool</h2>
  <h2>Other work (e.g. for punkt.de)</h2>
</template>
