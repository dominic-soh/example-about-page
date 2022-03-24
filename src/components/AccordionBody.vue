<template>
  <v-expansion-panels focusable>
    <v-expansion-panel>
      <v-expansion-panel-header>Contact</v-expansion-panel-header>
      <v-expansion-panel-content>
        <v-container>
          <v-row align="center" justify="center">
            <v-col cols="auto">
              <v-img :src="require('../assets/mail.png')" width="40" />
            </v-col>
            <v-col justify="center">15068671755@163.com</v-col>
          </v-row>
          <v-row align="center" justify="center">
            <v-col cols="auto">
              <v-img :src="require('../assets/phone.png')" width="40" />
            </v-col>
            <v-col justify="center">+86 17816610290</v-col>
          </v-row>
          <v-row align="center" justify="center">
            <v-col cols="auto">
              <v-img :src="require('../assets/home.png')" width="40" />
            </v-col>
            <v-col justify="center">
              The faculty of Mechanical Engineering and Automation, Zhejiang
              Sci-Tech University, Hangzhou China
            </v-col>
          </v-row>
        </v-container>
      </v-expansion-panel-content>
    </v-expansion-panel>
    <v-expansion-panel>
      <v-expansion-panel-header>Profile</v-expansion-panel-header>
      <v-expansion-panel-content>
        <h2>Research Interests</h2>
        <p class="font-weight-regular">
          Engineering Management, Operation Research, Mechanical Design
        </p>
        <h2>Education Background</h2>
        <p class="font-weight-regular">
          Zhejiang Sci-Tech University(Sep 2017-Jun 2021 Hangzhou, China)
          Bachelor of Engineering
        </p>
        <h3>Major:</h3>
        <p class="font-weight-regular">
          Mechanical Design and Manufacturing and Its Automation(in English),
          The faculty of Mechanical Engineering and Automation
        </p>
        <h3>GPA:81.4/100</h3>
      </v-expansion-panel-content>
    </v-expansion-panel>
    <v-expansion-panel>
      <v-expansion-panel-header>
        Professional Experience
      </v-expansion-panel-header>
      <v-expansion-panel-content>
        <h3>Positions held:</h3>
        <p class="font-weight-regular">
          Research Assistant<br />
          Zhejiang Sci-Tech University(Jun 2021-Present)<br />
          The Faculty of Mechanical Engineering and Automation(Hangzhou,China)
        </p>
        <h3>Project:</h3>
        <p class="font-weight-regular">
          Fault prediction and residual life evaluation method of the numerical
          control system, National Natural Science Foundation of China(51875529)
        </p>
        <v-container>
          <v-row align="center" justify="center" align-content="center"
            ><v-col cols="auto"
              ><v-img
                :src="require('../assets/bigbanner.png')"
                width="100%" /></v-col
          ></v-row>

          <v-row align="center" justify="center"
            ><v-col
              ><v-img
                :src="require('../assets/researchgraph1.png')"
                width="100%" /></v-col
          ></v-row>

          <v-row align="center" justify="center"
            ><v-col
              ><v-img
                :src="require('../assets/researchgraph2.png')"
                width="100%" /></v-col
          ></v-row>
        </v-container>
      </v-expansion-panel-content>
    </v-expansion-panel>
  </v-expansion-panels>
</template>

<script>
export default {
  name: "AccordionBody",

  data: () => ({}),
};
</script>
