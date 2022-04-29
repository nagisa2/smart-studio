<template>
  <div class="contact">
    <div class="contact-t">
      <h1>Are you ready for the unexpected?</h1>
      <p>Contact us today</p>
    </div>
    <div class="btn-con" @click="contact">
      <button class="btn-contact">Contact us</button>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  },

  methods: {
    contact() {
      window.open(
        "https://web.whatsapp.com/send?text=Hi?iam from your website&phone=0740754964",
        "Share with Whatsapp Web",
        "width=800,height=600"
      );
    },
  },
};
</script>

<style>
@import "../style/contact-us.css";
</style>
