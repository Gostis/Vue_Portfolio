<template>
  <div>
    <v-row id="section1" class="section">
      <v-col lg="6" sm="12" cols="6" align-self="center">
        <v-row>
          <h1 class="mainText display-4 font-weight-thin mb-4">
            Jacob Nyman
          </h1>
        </v-row>
        <v-row>
          <h1 class="mainText title font-weight-thin mb-4">
            - Full Stack developer | M.Sc student in Media Technology &
            Engineering
          </h1>
        </v-row>
        <v-row id="iconRow" no-gutters>
          <v-btn text icon color="black">
            <v-icon>fab fa-github</v-icon>
          </v-btn>

          <v-btn text icon color="black">
            <v-icon>far fa-envelope</v-icon>
          </v-btn>

          <v-btn text icon color="black">
            <v-icon>fab fa-linkedin</v-icon>
          </v-btn>

          <v-btn text icon color="black">
            <v-icon>fab fa-facebook</v-icon>
          </v-btn>
        </v-row>
      </v-col>
      <v-col cols="6" lg="6" sm="12" align-self="end" class="pa-0">
        <v-img
          src="../assets/Profile_image_only.png"
          aspect-ratio="1.1"
        ></v-img>
      </v-col>
    </v-row>
    <v-row id="section2" class="section" align="start">
      <v-col class="sectionTitle2" cols="3">
        <h1 class="display-4 font-weight-thin mb-4">Portfolio</h1>
      </v-col>
      <v-col class="sectionTitle2" cols="9">
        <v-row algin="center" no-gutters>
          <v-col cols="3" lg="3"> <ProjectModal /></v-col>
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
    <v-row id="section3" class="section" align="center" justify="center">
      <v-col class="text-center" cols="3">
        <h1 class="display-1 font-weight-thin mb-4">Resume</h1>
      </v-col>
    </v-row>
  </div>
</template>

<script>
// @ is an alias to /src
import ProjectModal from "../components/ProjectModal";
export default {
  name: "Home",
  components: { ProjectModal },
  methods: {
    onClick() {
      console.log("Hello");
    }
  }
};
</script>
<style>
#iconRow {
  padding-left: 20px;
}
.section {
  height: 100vh;
  width: 100%;
  margin: 0%;
}
#section1 {
  background: radial-gradient(
    circle,
    rgba(252, 252, 252, 1) 0%,
    rgba(205, 205, 205, 1) 100%
  );
}
#section2 {
  background-color: rgb(47, 47, 47, 1);
}
#section3 {
  background-color: rgb(49, 49, 49, 1);
}

.mainText {
  color: rgb(47, 47, 47, 1);
  justify-content: start;
  padding-left: 40px;
}

.sectionTitle2 {
  padding-top: 100px;
  padding-left: 50px;
}
</style>
