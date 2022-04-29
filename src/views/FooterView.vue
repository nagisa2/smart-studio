<template>
  <div class="footer">
    <div class="address">
      <h1>Address</h1>
      <span>Call us: 0740754964/0742483432,</span>
      <span>Captain Mungai street, Eastleigh,</span>
      <span>smartstudio1001@gmail.com</span>
    </div>
    <div class="company">
      <h1>Company</h1>
      <span>About us</span>
      <span>Careers</span>
      <span>Contact us</span>
    </div>
    <div class="follow-c">
      <h1>Follow us</h1>
      <div class="follow">
        <img
          src="../assets/whatsapp.svg"
          alt="whatsapp"
          class="whatsapp follow-icon"
          @click="whatsapp()"
        />
        <img
          src="../assets/Facebook.svg"
          alt="facebook"
          class="facebook follow-icon"
          @click="facebook()"
        />
        <img
          src="../assets/telegram.svg"
          alt="instagram"
          class="instagram follow-icon"
          @click="telegram()"
        />
        <img
          src="../assets/Twitter.svg"
          alt="twitter"
          class="twitter follow-icon"
          @click="twitter()"
        />
      </div>
    </div>
  </div>
</template>
<script>
export default {
  methods: {
    whatsapp() {
      window.open(
        "https://web.whatsapp.com/send?text=Hi?iam from your website&phone=0740754964",
        "Share with Whatsapp Web",
        "width=800,height=600"
      );
    },
    facebook() {
      window.open(
        "https://www.facebook.com/pg/qanciyeqawojiye",
        "Share with Whatsapp Web",
        "width=800,height=600"
      );
    },
    telegram() {
      window.open(
        "https://t.me/smartstudio4248",
        "Share with Whatsapp Web",
        "width=800,height=600"
      );
    },
    twitter() {
      window.open(
        "https://twitter.com/Smartstudio4248",
        "Share with Whatsapp Web",
        "width=800,height=600"
      );
    },
  },
};
</script>

<style>
@import "../style/Footer.css";
</style>
