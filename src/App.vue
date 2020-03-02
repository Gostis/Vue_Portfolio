<template>
  <v-app>
    <Header />
    <Home />
  </v-app>
</template>

<script>
import Header from "./components/layout/Header";
import Home from "./views/Home";
export default {
  name: "App",

  components: {
    Header,
    Home
  },

  data: () => ({
    //
  })
};
</script>
