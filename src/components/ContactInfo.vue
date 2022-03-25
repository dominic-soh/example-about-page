<template>
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
        The faculty of Mechanical Engineering and Automation, Zhejiang Sci-Tech
        University, Hangzhou China
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "ContactInfo",

  data: () => ({}),
};
</script>
