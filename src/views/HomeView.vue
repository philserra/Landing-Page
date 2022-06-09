<template>
  <div class="home">
    <Navbar />
    <Jumbottron />
    <CTA />
    <Card />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "../components/Navbar.vue";
import Jumbottron from "../components/Jumbottron.vue";
import CTA from "../components/CTA.vue";
import Card from "../components/Card.vue";
import Footer from "../components/Footer.vue";
export default {
  name: "HomeView",
  components: {
    Navbar,
    Jumbottron,
    CTA,
    Card,
    Footer,
  },
};
</script>
