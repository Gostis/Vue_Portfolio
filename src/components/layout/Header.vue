<template>
  <v-app-bar :class="{Navbar: isTop, NavbarTop: !isTop}" flat fixed app>
    <v-spacer></v-spacer>

    <v-toolbar-title class="title">
      <router-link to="/">Home</router-link>
    </v-toolbar-title>
    <v-toolbar-title class="title">
      <router-link to="/portfolio">Portfolio</router-link>
    </v-toolbar-title>
    <v-toolbar-title class="title">
      <router-link to="/resume">Resume</router-link>
    </v-toolbar-title>
    <v-toolbar-title class="title">
      <router-link to="/about">About</router-link>
    </v-toolbar-title>

    <v-spacer></v-spacer>
  </v-app-bar>
</template>





<script>
export default {
  name: "Header",
  data: () => ({
    isTop: false
  }),

  methods: {
    updateScroll() {
      this.isTop = window.scrollY;
    }
  },
  mounted() {
    window.addEventListener("scroll", this.updateScroll);
  }
};
</script>

<style scoped>
.title {
  padding: 10px;
}
.Navbar {
  background-color: rgb(40, 40, 40) !important;
}
.NavbarTop {
  background-color: rgb(255, 0, 0, 0.02) !important;
}
</style>
