<template>
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
</template>
