<template>
  <v-dialog v-model="dialog" width="600">
    <template v-slot:activator="{ on }">
      <v-card v-on="on" class="sizeBox" outlined tile>1</v-card>
    </template>

    <v-card class="modal">
      <h1 class="mainText display-1 font-weight-thin mb-4">Bachelor thesis: Animal Approach</h1>

      <v-row align="center" justify="center" no-gutters>
        <v-col cols="auto">
          <v-img src="../assets/animal_approach.png" height="300px" width="500px"></v-img>
        </v-col>
      </v-row>
      <v-row>
        <v-col class="bodyText">
          <p>The bachelor thesis in Media Technology and Engineering was a project with focus on agile development. The students of the course were divided into groups based on what projects ideas they were interested in. The project that I was assigned to was to create a multiplayer game in AR. The focus of the project was to create a game that felt inclusive and mimicked the feeling of a board game. The fundamental concepts of the project was network, tracking and game development.</p>
        </v-col>
      </v-row>
      <v-row>
        <h1 class="mainText title font-weight-thin mb-4">About the project</h1>
      </v-row>
      <v-row>
        <v-col class="bodyText">
          <p>The game that was created was a capture the flag game played in teams. The player could choose between different characters(heroes) to play that all had different strengths and weaknesses. These strengths and weaknesses are shown through their unique abilities i.e strength, speed, intellect. The games playing field was generated in AR with procedurally generated game assets. The players used their mobile devices as windows to the playing field and the players all see the same playing field, with the help of server/client connection between all included devices. In order to succeed with this markers was used with the AR tracking. As the game was rendered on mobile devices the polygon count had to be taken into consideration. This issue was handled through modeling the games assets in low-poly graphics. The game was developed entirely in Unity coding in C#. All of the game assets were modeled by the project team in Blender.</p>
        </v-col>
      </v-row>
      <v-row class="chips">
        <v-chip class="ma-2">Unity</v-chip>
        <v-chip class="ma-2">Scrum</v-chip>
        <v-chip class="ma-2">Agile development</v-chip>
        <v-chip class="ma-2">Augmented Reality</v-chip>
        <v-chip class="ma-2">Vuforia</v-chip>
        <v-chip class="ma-2">3D-modeling</v-chip>
        <v-chip class="ma-2">3D-animation</v-chip>
        <v-chip class="ma-2">Multiplayer</v-chip>
        <v-chip class="ma-2">Network</v-chip>
        <v-chip class="ma-2">Mobile game</v-chip>
        <v-chip class="ma-2">Android</v-chip>
        <v-chip class="ma-2">Gameplay</v-chip>
        <v-chip class="ma-2">Abilities</v-chip>
        <v-chip class="ma-2">Procedural map generation</v-chip>
        <v-chip class="ma-2">C#</v-chip>
      </v-row>
    </v-card>
  </v-dialog>
</template>

<script>
export default {
  name: "ProjectModal"
};
</script>

<style>
.modal {
  overflow-x: hidden;
}
.bodyText {
  margin: 20px;
}
.chips {
  margin: 10px 2px 0 2px;
}
</style>
