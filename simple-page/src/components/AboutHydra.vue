<template>
  <div class="about-container">
    <div class="image-container">
      <img :src="virtualRealityMan" alt="" />
    </div>
    <div class="text-container">
      <div class="title-container">
        <h2>
          <span class="bold-text"> About </span>
        </h2>
        <h2>
          <span class="thin-text"> Hydra vr </span>
        </h2>
      </div>
      <div class="text-box">
        <p>
          Eget mi proin sed libero enim sed faucibus turpis. Nisl rhoncus mattis
          rhoncus urna neque viverra justo. Vivamus at augue eget arcu dictum.
          Ultrices lastre dictum fusce ut placerat orci. Aenean et tortor at
          risus viverra adipiscing at in. Mattis aliquam faucibus purus in
          massa. Est placerat in egestas erat imperdiet sed. Consequat semper
          viverra nam libero justo laoreet sit amet. Aliquam etiam erat velit
          scelerisque in dictum non consectetur a. Laoreet sit amet cursus sit
          amet. Vel eros donec ac odio tempor orci dapibus. Sem nulla pha retra
          diam sit amet nisl suscipit adipiscing bibendum. Leo a diam
          sollicitudi n tempor.
        </p>
      </div>
      <a class="btn" href="#">Let's get in touch</a>
    </div>
  </div>
</template>

<script>
import virtualRealityMan from "../assets/images/man-virtual-reality.svg";

export default {
  name: "AboutHydra",
  data() {
    return {
      virtualRealityMan,
    };
  },
};
</script>

<style>
.about-container {
  display: flex;
}

.bold-text {
  position: relative;
}

.text-container > .btn {
  display: inline-block;
  text-decoration: none;
  text-transform: uppercase;
  color: #343045;
  background: linear-gradient(to left, #8176af, #c0b7e8);
  padding: 0.7rem 2rem;
  border-radius: 32px;
  font-weight: 700;
  font-size: 14px;
  font-family: "montserrat", sans-serif;
}

.text-container > .btn:active {
  transform: scale(0.95);
}
</style>
