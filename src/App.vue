<template>
  <v-app>
    <v-app-bar
      app
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="OpenAtlas Logo"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src="/assets/logo.png"
          width="100"
        />
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://www.openatlas.eu/"
        target="_blank"
        text
      >
        <span class="mr-2">OpenAtlas Website</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
