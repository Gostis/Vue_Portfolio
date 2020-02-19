<template>
  <v-container class="grey lighten-5">
    <v-row algin="center" justify="space-around" no-gutters>
      <v-col class="spaceBetween" lg="3">
        <v-card class="sizeBox" outlined tile>1</v-card>
      </v-col>
      <v-col cols="1" lg="3">
        <v-card class="sizeBox" outlined tile>1</v-card>
      </v-col>
      <v-col cols="1" lg="3">
        <v-card class="sizeBox" outlined tile>1</v-card>
      </v-col>
      <v-col cols="1" lg="3">
        <v-card class="sizeBox" outlined tile>1</v-card>
      </v-col>
    </v-row>
    <v-row class="boxSpace" no-gutters>
      <v-col cols="1" lg="3">
        <v-card class="sizeBox" outlined tile>1</v-card>
      </v-col>
      <v-col cols="1" lg="3">
        <v-card class="sizeBox" outlined tile>1</v-card>
      </v-col>
      <v-col cols="1" lg="3">
        <v-card class="sizeBox" outlined tile>1</v-card>
      </v-col>
      <v-col cols="1" lg="3">
        <v-card class="sizeBox" outlined tile>1</v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "Portfolio"
};
</script>

<style>
.sizeBox {
  width: 500px;
  height: 300px;
}
.boxSpace {
  margin-top: 20px;
}
</style>