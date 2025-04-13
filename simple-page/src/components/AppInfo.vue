<template>
  <div class="info-container">
      <div class="image-container">
        <h3>Pay Us a Visit</h3>
        <p>Union St, Seattle, WA 98101, United States</p>
        <img :src="location" alt="">
      </div>
      <div class="image-container">
        <h3>Give Us a Call</h3>
        <p>(110) 1111-1010</p>
        <img :src="envelope" alt="">
      </div>
      <div class="image-container">
        <h3>Send Us a Message</h3>
        <p>Contact@HydraVTech.com</p>
        <img :src="phone" alt="">
      </div>
  </div>
</template>

<script>
import location from "../assets/images/location.svg";
import envelope from "../assets/images/envelope.svg";
import phone from "../assets/images/phone.svg";

export default {
  name: "AppInfo",
  data() {
    return {
      location,
      envelope,
      phone,
    };
  },
};
</script>