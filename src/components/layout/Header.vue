<template>
  <v-app-bar :class="{Navbar: isTop, NavbarTop: !isTop}" flat fixed app>
    <v-spacer></v-spacer>

    <v-toolbar-title class="title">
      <p text class="cursor" v-scroll-to="'#section1'">Home</p>
    </v-toolbar-title>
    <v-toolbar-title class="title">
      <p class="cursor" v-scroll-to="'#section2'">Portfolio</p>
    </v-toolbar-title>
    <v-toolbar-title class="title">
      <p class="cursor" v-scroll-to="'#section3'">Resume</p>
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
  background-color: rgb(255, 255, 255, 0.02) !important;
}

.cursor {
  cursor: pointer;
}
</style>
