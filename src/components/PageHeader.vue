<template>
  <v-container style="width: 80%">
    <v-row>
      <v-col align="right">
        <v-img
          :src="require('../assets/jiangchill.jpg')"
          class="my-3"
          contain
          height="300"
          width="300"
        />
      </v-col>

      <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">Jiang Junhui</h1>

        <p class="subheading font-weight-regular">Bachelor of Engineering</p>
        <contact-info />
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import ContactInfo from "./ContactInfo.vue";

export default {
  name: "HelloWorld",
  components: { ContactInfo },

  data: () => ({}),
};
</script>
