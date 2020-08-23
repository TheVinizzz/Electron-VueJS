<template>
  <v-app>
    <v-app-bar dark absolute>
      <v-toolbar-title>Electron Teste</v-toolbar-title>
    </v-app-bar>

    <v-content class="ramdamB">
      <Home />
    </v-content>
  </v-app>
</template>

<script>
import Home from "./components/Home";
export default {
  name: "App",

  components: {
    Home,
  },

  data: () => ({
    //
  }),
};
</script>
<style>
.barra {
  height: 1px;
}
.ramdamB {
  margin-top: 70px;
}
</style>
