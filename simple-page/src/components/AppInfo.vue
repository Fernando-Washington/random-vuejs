<template>
  <div class="info-container">
    <!-- first block -->
    <div class="image-container">
      <img class="info-icon" :src="location" alt="" />
      <br />
    </div>
    <div class="text-container">
      <h3>Pay Us a Visit</h3>
      <p>Union St, Seattle, WA 98101, United States</p>
    </div>

    <!-- second block -->
    <div class="image-container">
      <img class="info-icon" :src="envelope" alt="" />
      <br />
    </div>
    <div class="text-container">
      <h3>Give Us a Call</h3>
      <p>(110) 1111-1010</p>
    </div>

    <!-- third block-->
    <div class="image-container">
      <img class="info-icon" :src="phone" alt="" />
      <br />
    </div>
    <div class="text-container">
      <h3>Send Us a Message</h3>
      <p>Contact@HydraVTech.com</p>
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

<style>
.info-container {
  display: flex;
  transform: scale(0.8);
  align-items: center;
  background: linear-gradient(90deg, #8176afb9, #252525b9);
  padding: 1rem;
  border-radius: 300px;
}

.image-container {
  padding: 1rem 0 1rem 1rem;
}

.text-container {
  padding: 1rem 1rem 1rem 0;
  font-family: "montserrat", sans-serif;
}

.text-container > h3 {
  position: relative;
  top: 18px;
  color: #ffffff;
}

.image-container > .info-icon {
  width: 48px;
}
</style>
