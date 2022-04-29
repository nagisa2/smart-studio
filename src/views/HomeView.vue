<template>
  <div class="home">
    <div class="home-h p2">
      <div class="img">
        <img
          src="../assets/triangle.svg"
          alt="triangle"
          class="triangle home-t"
        />
      </div>
      <div class="hero">
        <div class="hero-txt">
          <h1>We <span>create</span> something new</h1>
          <p>
            Here at smart studio we bring designs to life and with our
            photography capture every
          </p>
        </div>
        <div class="hero-button">
          <button class="btn-hero btn-1" @click="project">Our project</button>
          <button class="btn-hero btn-2" @click="about">About us</button>
        </div>
      </div>
    </div>
    <div class="middle-c">
      <span class="middle-img"> </span>
      <div><hr class="hr" /></div>
      <div class="middle">
        <img src="../assets/tri-play.svg" alt="play" class="tri-play" />
        <div>
          <img src="../assets/play-tri.svg" alt="play" class="play-tri" />
        </div>
      </div>
    </div>
    <div class="home-y p2">
      <img src="../assets/Bgpic.jpg" alt="bg-image" class="bg-image" />
    </div>
  </div>
  <div class="home-pad">
    <Clients />
    <Project class="upto" />
    <Services />
    <About />
    <Feedback />
    <Job />
    <News class="n-t" />
    <ContactUs class="n-t n-c" />
    <Footer class="n-t" />
  </div>
</template>
<script setup>
import Feedback from "../components/customer-feedback.vue";
import Services from "../components/OurServices.vue";
import ContactUs from "../components/contact-us.vue";
import Clients from "../components/OurClients.vue";
import News from "../components/NewsComponent.vue";
import Job from "../components/job-analysis.vue";
import Project from "../views/ProjectView.vue";
import Footer from "../views/FooterView.vue";
import About from "../views/AboutView.vue";
</script>
<script>
export default {
  data() {
    return {};
  },

   methods: {
    project() {
      this.$router.push("/project");
    },
    about() {
      this.$router.push("/about");
    },
  },
};
</script>

<style>
@import "../style/HomeView.css";
</style>
