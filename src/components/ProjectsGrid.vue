<template>
  <v-row>
    <v-col class="sectionTitle2" cols="3">
      <h1 class="display-4 font-weight-thin mb-4">Portfolio</h1>
    </v-col>
    <v-col class="sectionTitle2" cols="9">
      <v-row algin="center" no-gutters>
        <v-col cols="3" lg="3">
          <ProjectModal />
        </v-col>
        <v-col cols="3" lg="3">
          <v-card class="sizeBox" outlined tile>1</v-card>
        </v-col>
        <v-col cols="3" lg="3">
          <v-card class="sizeBox" outlined tile>1</v-card>
        </v-col>
        <v-col cols="3" lg="3">
          <v-card class="sizeBox" outlined tile>1</v-card>
        </v-col>
      </v-row>
      <v-row algin="center" no-gutters>
        <v-col cols="3" lg="3">
          <v-card class="sizeBox" outlined tile>1</v-card>
        </v-col>
        <v-col cols="3" lg="3">
          <v-card class="sizeBox" outlined tile>1</v-card>
        </v-col>
        <v-col cols="3" lg="3">
          <v-card class="sizeBox" outlined tile>1</v-card>
        </v-col>
        <v-col cols="3" lg="3">
          <v-card class="sizeBox" outlined tile>1</v-card>
        </v-col>
      </v-row>
    </v-col>
  </v-row>
</template>

<script>
import ProjectModal from "./ProjectModal";

export default {
  name: "Portfolio",
  components: { ProjectModal }
};
</script>

<style>
</style>