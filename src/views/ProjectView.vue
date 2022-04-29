<template>
  <div class="img-container">
    <div class="img-h-txt">
      <h1>What we've been upto</h1>
      <h3>some of our finest works</h3>
    </div>
    <div class="img">
      <img src="../assets/triangle.svg" alt="triangle" class="triangle-p" />
      <div class="layout-container">
        <div class="img-layout">
          <img
            src="../assets/design1.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/design2.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/design11.jpg"
            alt="project image"
            class="project-img"
          />
          <img src="../assets/p1.jpg" alt="project image" class="project-img" />
        </div>
        <div class="img-layout">
          <img
            src="../assets/design3.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/p10.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/p13.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/design26.jpg"
            alt="project image"
            class="project-img"
          />
        </div>
        <div class="img-layout">
          <img
            src="../assets/design6.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/design24.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/design5.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/p22.jpg"
            alt="project image"
            class="project-img"
          />
        </div>
        <div class="img-layout hide">
          <img
            src="../assets/design25.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/design7.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/p16.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/design9.jpg"
            alt="project image"
            class="project-img"
          />
        </div>
        <div class="img-layout hide">
          <img
            src="../assets/design23.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/design8.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/p19.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/design18.jpg"
            alt="project image"
            class="project-img"
          />
        </div>
        <div class="img-layout hide">
          <img
            src="../assets/design19.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/p33.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/p19.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/design12.jpg"
            alt="project image"
            class="project-img"
          />
        </div>
        <div class="img-layout hide">
          <img
            src="../assets/design16.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/p38.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/p16.jpg"
            alt="project image"
            class="project-img"
          />
          <img
            src="../assets/design17.jpg"
            alt="project image"
            class="project-img"
          />
        </div>
      </div>
    </div>
    <div class="align">
      <button class="btn-img" @click="project">View all our project</button>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  },

  methods: {
    project() {
      this.$router.push("/project");
    },
  },
};
</script>
<style>
@import "../style/ProjectView.css";
</style>
