<template>
  <v-container>
    <v-row>
      <v-col>
        <v-img
          :src="require('../assets/biggo.png')"
          class="my-3"
          contain
          height="200"
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
