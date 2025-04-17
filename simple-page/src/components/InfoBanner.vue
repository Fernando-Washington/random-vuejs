<template>
  <div class="container">
    <div class="title-container">
      <h2>
        <span class="bold-text"> Introduction </span>
      </h2>
      <h2>
        <span class="thin-text"> To hydra vr </span>
      </h2>
    </div>
    <div class="arrow-container">
      <img :src="largeArrow" alt="Arrow" />
    </div>
    <div class="text-container">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cumque, placeat molestias optio maiores mollitia, a sequi nam provident, quae modi temporibus laboriosam saepe dolorem iusto ab cupiditate! Doloribus, eaque voluptates.
        Facilis veritatis qui tempora inventore officiis architecto ducimus velit ipsum enim labore</p>
    </div>
  </div>
</template>

<script>
import vrMan from "../assets/images/man-virtual-reality.svg";
import largeArrow from "../assets/images/large-arrow.svg";

export default {
  name: "InfoBanner",
  data() {
    return {
      vrMan,
      largeArrow,
    };
  },
};
</script>

<style>
.container {
  display: flex;
  align-items: center;
  padding: 1rem;
  justify-content: center;
  transform: scale(0.95);
  gap: 2.4rem;
}

.container > .text-container {
  flex: 1;
}

.arrow-container {
    position: relative;
    top: 22px;
    left: -72px;
}

.bold-text {
  color: #ffffff;
  font-family: "montserrat", sans-serif;
  text-transform: uppercase;
  font-size: 32px;
  margin-bottom: 1rem;
}

.thin-text {
  font-family: "montserrat", sans-serif;
  color: #8176af;
  font-size: 30px;
  font-weight: 300;
  text-transform: uppercase;
}

.container > .text-container {
  display: flex;
  flex-direction: column;
  flex: 1;
  min-height: 120px;
  height: auto;
}
</style>
<!-- maybe I need to center this element, wrap and fn-sz-->