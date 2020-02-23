<template>
  <v-dialog v-model="dialog" width="1000">
    <template v-slot:activator="{ on }">
      <v-card v-on="on" class="sizeBox" outlined tile>1</v-card>
    </template>

    <v-card>
      <v-card-title class="headline grey lighten-2" primary-title
        >Project 1</v-card-title
      >
    </v-card>
  </v-dialog>
</template>

<script>
export default {
  name: "ProjectModal"
};
</script>

<style></style>
