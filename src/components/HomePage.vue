<template>
  <v-conatiner>
    <v-row class="main d-sm-flex justify-center">
      <v-col
        cols="10"
        sm="5"
        md="3"
        class="pa-0 left d-flex justify-center justify-sm-end"
      >
        <!-- <div class="cardw d-flex justify-end"> -->
        <div class="card d-flex justify-center pa-2">
          <v-row class="d-flex justify-center align-center">
            <v-col
              cols="12"
              class="pa-0 mb-3 d-flex justify-center align-center"
            >
              <div class="text heading2 lavtext mb-5">Your Result</div>
            </v-col>
            <v-col cols="12" class="d-flex justify-center align-center">
              <div class="circle d-flex flex-column align-center ma-0 pa-0">
                <div class="seven text text-white mt-13 mt-sm-5 circletext d-flex ma-0 pa-0">
                  76
                </div>
                <div class="seven text lavtext circletext2 d-flex mb-1">of 100</div>
              </div>
            </v-col>

            <v-col
              cols="12"
              class="d-flex flex-column text-center align-center mt-5"
            >
              <div class="text great mt-5">Great</div>

              <div class="text2 mt-5 lavtext px-5">
                You scored higher than 65% of the people who have taken these
                test.
              </div>
            </v-col>
          </v-row>
        </div>
        <!-- </div> -->
      </v-col>

      <v-col
        cols="10"
        sm="5"
        md="3"
        class="pa-0 right d-flex justify-center justify-sm-start"
      >
        <div class="card2 pa-2">
          <v-col cols="12">
            <div class="text heading text-grey-darken-3">Summary</div>
          </v-col>

          <v-col cols="12">
            <v-col
              cols="12"
              class="list list1 rounded-1 d-flex align-center mb-3 pa-0"
            >
              <v-col cols="7" class="">
                <v-icon
                  color=""
                  icon="mdi-lightning-bolt-outline"
                  size="small"
                  class="pa-0 mr-2 one"
                ></v-icon>
                <span class="text one">Reaction</span>
              </v-col>
              <v-col cols="5" class="d-flex flex-wrap align-center justify-end">
                <div class="l text-grey-darken-3 font-weight-bold mr-1">80</div>
                <div class="r text-grey">/ 100</div>
              </v-col>
            </v-col>

            <v-col
              cols="12"
              class="list list2 bg-light-green rounded-1 d-flex align-center mb-3 pa-0"
            >
              <v-col cols="7" class="">
                <v-icon
                  color=""
                  icon="mdi-brain"
                  size="small"
                  class="two pa-0 mr-2"
                ></v-icon>
                <span class="text two">Memory</span>
              </v-col>
              <v-col cols="5" class="d-flex flex-wrap align-center justify-end">
                <div class="l text-grey-darken-3 font-weight-bold mr-1">92</div>
                <div class="r text-grey">/ 100</div>
              </v-col>
            </v-col>

            <v-col
              cols="12"
              class="list list3 bg-light-green rounded-1 d-flex align-center mb-3 pa-0"
            >
              <v-col cols="7" class="">
                <v-icon
                  color=""
                  icon="mdi-chat-processing-outline"
                  size="small"
                  class="three pa-0 mr-2"
                ></v-icon>
                <span class="text three">Verbal</span>
              </v-col>
              <v-col cols="5" class="d-flex flex-wrap align-center justify-end">
                <div class="l text-grey-darken-3 font-weight-bold mr-1">61</div>
                <div class="r text-grey">/ 100</div>
              </v-col>
            </v-col>

            <v-col
              cols="12"
              class="list list4 bg-light-green rounded-1 d-flex align-center pa-0"
            >
              <v-col cols="7" class="">
                <v-icon
                  color=""
                  icon="mdi-eye-outline"
                  size="small"
                  class="four pa-0 mr-2"
                ></v-icon>
                <span class="text four">Visual</span>
              </v-col>
              <v-col cols="5" class="d-flex flex-wrap align-center justify-end">
                <div class="l text-grey-darken-3 font-weight-bold mr-1">72</div>
                <div class="r text-grey">/ 100</div>
              </v-col>
            </v-col>
          </v-col>

          <v-col cols="12"
            ><v-btn
              rounded="xl"
              size="large"
              class="continue text-capitalize"
              flat
              block
              >Continue</v-btn
            ></v-col
          >
        </div>
      </v-col>
    </v-row>
  </v-conatiner>
</template>


<style scoped>
@font-face {
  font-family: f1;
  src: url(@/assets/HankenGrotesk-Bold.ttf);
}
@font-face {
  font-family: f2;
  src: url(@/assets/HankenGrotesk-ExtraBold.ttf);
}
@font-face {
  font-family: f3;
  src: url(@/assets/HankenGrotesk-Medium.ttf);
}
@font-face {
  font-family: f4;
  src: url(@/assets/HankenGrotesk-VariableFont_wght.ttf);
}
.circle {
  width: 12vw; /* 20% of the viewport width */
  height: 12vw; /* 20% of the viewport width to maintain a 1:1 aspect ratio */
  background-image: linear-gradient(
    to bottom,
    hsla(256, 72%, 46%, 1),
    hsla(241, 72%, 46%, 0)
  );
  border-radius: 50%; /* This creates the circle */
  position: absolute;
}
.circletext {
  font-size: 5vw;
}
.circletext2 {
  font-size: 1.2vw;
}
.card {
  width: 90%;
  height: 400px;
  background-image: linear-gradient(
    to bottom,
    hsl(252, 100%, 67%),
    hsl(241, 81%, 54%)
  );
  border-radius: 30px;
  box-shadow: 0px 0px 20px 0px rgba(85, 58, 247, 0.2);
}
.card2 {
  width: 90%;
  height: 400px;
  background-color: #ffffff;
  border-radius: 30px;
  box-shadow: 0px 0px 20px 0px rgba(85, 58, 247, 0.2);
}
.main {
  margin-top: 7.5%;
}
.list {
  width: 100%;
  height: 8vh;
  border-radius: 10px;
}
.list1 {
  background: linear-gradient(to right, #fef5f5, #fff5f5);
}
.list2 {
  background: linear-gradient(to right, #fefbf1, #fffaf2);
}
.list3 {
  background: linear-gradient(to right, #f0fbfb, #f2fbf8);
}
.list4 {
  background: linear-gradient(to right, #f2f2fd, #f3f2fc);
}
.continue {
  background-color: #303b59;
  color: aliceblue;
}
.continue:hover {
  background-image: linear-gradient(
    to bottom,
    hsl(252, 100%, 67%),
    hsl(241, 81%, 54%)
  );
  color: aliceblue;
}
.one {
  color: hsl(0, 100%, 67%);
  font-family: f1;
}
.two {
  color: hsl(39, 100%, 56%);
  font-family: f1;
}
.three {
  color: hsl(166, 100%, 37%);
  font-family: f1;
}
.four {
  color: hsl(234, 85%, 45%);
  font-family: f1;
}
.text {
  font-family: f1;
}
.text2 {
  font-family: f4;
}
.heading {
  font-size: 20px;
}
.heading2 {
  font-size: 20px;
}
.lavtext {
  color: hsl(241, 100%, 89%);
}
.great {
  color: aliceblue;
  font-size: 30px;
}
@media screen and (max-width: 600px) {
  .circle {
    width: 32vw; /* 20% of the viewport width */
    height: 32vw; /* 20% of the viewport width to maintain a 1:1 aspect ratio */
  }
  .seven {
    margin-top: 30px;
    padding-bottom: 0px;
    scale: 3;
    transform-origin: center;
  }
  .card {
    width: 70%;
  }
  .card2 {
    width: 70%;
  }
}
</style>