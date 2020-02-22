<template>
  <div>
    <v-row id="section1" class="section" align="center" justify="center">
      <v-col lg="6" sm="12" cols="6">
        <v-row>
          <h1 class="mainText display-4 font-weight-thin mb-4">Jacob Nyman</h1>
        </v-row>
        <v-row>
          <h1
            class="mainText title font-weight-thin mb-4"
          >- Full Stack developer | M.Sc student in Media Technology & Engineering</h1>
        </v-row>
      </v-col>
      <v-col cols="6" lg="6" sm="12">
        <v-img src="../assets/Profile_image_only.png" aspect-ratio="1.1"></v-img>
      </v-col>
    </v-row>
    <v-row id="section2" class="section" align="start">
      <v-col class="sectionTitle2" cols="3">
        <h1 class="display-4 font-weight-thin mb-4">Portfolio</h1>
      </v-col>
      <v-col class="sectionTitle2" cols="9">
        <v-row algin="center" no-gutters>
          <v-col cols="3" lg="3">
            <v-dialog v-model="dialog" width="1000">
              <template v-slot:activator="{ on }">
                <v-card v-on="on" class="sizeBox" outlined tile>1</v-card>
              </template>

              <v-card>
                <v-card-title class="headline grey lighten-2" primary-title>Privacy Policy</v-card-title>

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
              </v-card>
            </v-dialog>
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
    <v-row id="section3" class="section" align="center" justify="center">
      <v-col class="text-center" cols="3">
        <h1 class="display-1 font-weight-thin mb-4">Resume</h1>
      </v-col>
    </v-row>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
  methods: {
    onClick() {
      console.log("Hello");
    }
  }
};
</script>
<style scoped>
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
  padding-left: 20px;
}

.sectionTitle2 {
  padding-top: 100px;
  padding-left: 50px;
}
</style>
