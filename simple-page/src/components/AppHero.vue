<template>
  <main>
    <div class="text-container">
      <h2>
        <span class="text-gradient">Dive</span>
        Into The Depths
      </h2>
      <h2>
        Of
        <span class="text-gradient">Virtual Reality</span>
      </h2>
      <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sapiente
        laudantium error eveniet vel ab sequi suscipit illum culpa maxime velit
        aspernatur perferendis voluptas rem aliquam
      </p>

      <a class="btn" href="#">Build your world</a>
      <img :src="arrowRight" alt="" />
    </div>
    <div class="image-container">
      <img :src="virtualReality" alt="" />
    </div>
  </main>
</template>

<script>
import virtualReality from "../assets/images/girl-virtual-reality.svg";
import arrowRight from "../assets/images/arrow.svg";

export default {
  data() {
    return {
      virtualReality,
      arrowRight,
    };
  },
};
</script>

<style>
main {
  display: flex;
  padding: 2rem 0rem 2rem 3rem;
  color: #ffffff; /* Texto branco */
}

.text-container {
  flex: 1;
  margin-right: 6rem;
}

.text-container h2 {
  font-family: "Montserrat", sans-serif;
  font-size: 3rem;
  font-weight: 700;
  line-height: 1.2;
  margin: 0;
}

.text-container > h2 > .text-gradient {
  background: linear-gradient(90deg, #8176af, #c0b7e8);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.text-container p {
  font-family: "Montserrat", sans-serif;
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.6;
  margin: 1.5rem 0;
  color: #ffffff;
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

.text-container > img {
  position: relative;
  top: 14px;
  left: 40px;
}

.image-container {
  display: flex;
  align-items: center;
  justify-content: center;
  flex: 1;
}

.image-container > img {
  width: 100%;
  max-width: 432px;
}
</style>
