<template color="#445064">
  <v-container fluid class="text-xs-center">
    <v-layout justify-center :align-center="$vuetify.breakpoint.mdAndUp" fill-height>
      <v-flex xs12 md10>
        <h1 class="title my-5">About Live Torrent</h1>

        <p>Live Torrent created to explore, share and play media of torrent files online.</p>
        <p>
          Live Torrent is open source.
          <br />
        </p>
        <p><a href="https://ttttt.me/ITHARD">Telegram channel</a></p>
        
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: "about",
  created() {
    document.title = "Live Torrent - About";
  }
};
</script>
