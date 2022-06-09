<template>
  <carousel></carousel>
  <img :src="img" />
  <router-view />
</template>

<script>
import Carousel from "../src/components/Carousel.vue";
export default {
  name: "app",
  components: { Carousel },
  data: () => ({
    slides:
      // "https://picsum.photos/id/1037/900/400",
      // "https://picsum.photos/id/1037/900/400",
      // "https://picsum.photos/id/1037/900/400",
      // "https://picsum.photos/id/1037/900/400",
      // "https://picsum.photos/id/1037/900/400",
      "",
    el: "",
  }),
  methods: {
    img: function (el) {
      this.slides = "https://picsum.photos/id/1037/900/400";
      this.el = "hello";
    },
  },
};
</script>

<style></style>
