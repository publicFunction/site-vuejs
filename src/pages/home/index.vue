<template>
  <v-layout>
    <v-panel
      contextual-style="primary"
    >
      <h1 class="panel-title" slot="heading">
        Featured Video
      </h1>
      <div slot="body">
        Video goes here
      </div>
      <div slot="footer">
        Any additional Information goes here
      </div>
    </v-panel>
  </v-layout>
</template>

<script>
  /* ============
   * Home Index Page
   * ============
   *
   * The home index page.
   */

  export default {
    components: {
      VLayout: require('@/layouts/default.vue'),
      VPanel: require('@/components/featured.vue'),
    },
  };
</script>
