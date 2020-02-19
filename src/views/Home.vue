<template>
  <div>
    <v-row id="section1" class="section" align="center" justify="center">
      <v-col class="text-center" cols="12">
        <h1 class="display-1 font-weight-thin mb-4">Section 1</h1>
      </v-col>
    </v-row>
    <v-row id="section2" class="section" align="center" justify="center">
      <v-col class="text-center" cols="12">
        <h1 class="display-1 font-weight-thin mb-4">Section 2</h1>
      </v-col>
    </v-row>
    <v-row id="section3" class="section" align="center" justify="center">
      <v-col class="text-center" cols="12">
        <h1 class="display-1 font-weight-thin mb-4">Section 3</h1>
      </v-col>
    </v-row>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {}
};
</script>
<style scoped>
.section {
  height: 100vh;
  width: 100%;
}
#section1 {
  background-color: aquamarine;
}
#section2 {
  background-color: burlywood;
}
#section3 {
  background-color: darkgreen;
}
</style>
