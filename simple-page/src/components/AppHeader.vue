<template>
  <header>
    <div class="logo-container">
      <img class="logo" :src="logo" alt="" />
      <img :src="hydra" alt="" />
    </div>
    <nav>
      <ul>
        <li>About</li>
        <li>Services</li>
        <li>Technologies</li>
        <li>How to</li>
      </ul>
    </nav>
    <div class="contact-container">
      <a class="contact-btn" href="#">CONTACT US</a>
      <a class="join-btn" href="#">JOIN HYDRA</a>
    </div>
  </header>
</template>

<script>
import logo from "@/assets/images/logo.svg";
import hydra from "@/assets/images/hydra.svg";

export default {
  name: "AppHeader",
  data() {
    return {
      logo,
      hydra,
    };
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap");

header {
  width: 100%;
  height: 72px;
  padding: 1rem 0.4rem;
  display: flex;
  justify-content: space-between;
}

.logo-container {
  width: auto;
  height: 100%;
  display: flex;
  align-items: center;
}

.logo {
  width: 72px;
  margin: 0 1rem;
  padding-top: 0.6rem;
}

nav {
  padding: 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
}

nav > ul {
  display: flex;
  gap: 3rem;
  list-style: none;
}

nav > ul > li {
  font-family: "montserrat", sans-serif;
  font-weight: bold;
  color: #ffffff;
  font-size: 14px;
  text-transform: uppercase;
  cursor: pointer;
  transition: 0.3s ease-in-out;
}

nav > ul > li:hover {
  color: #8176af;
}

.contact-container {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 4rem;
  width: 35%;
}

.contact-container > .contact-btn {
  text-decoration: none;
  color: white;
  padding: 0.6rem 1.6rem;
  border: solid 2px #fff;
  border-radius: 32px;
  font-weight: 600;
  font-size: 14px;
  font-family: "montserrat", sans-serif;
}

.contact-container > .contact-btn:active {
  transform: scale(0.95);
  color: #c0b7e8;
  border-color: #c0b7e8;
}

.contact-container > .join-btn {
  text-decoration: none;
  color: #343045;
  background: linear-gradient(to left, #8176af, #c0b7e8);
  padding: 0.7rem 1.7rem;
  border-radius: 32px;
  font-weight: 600;
  font-size: 14px;
  font-family: "montserrat", sans-serif;
}

.contact-container > .join-btn:active {
  transform: scale(0.95);
}
</style>
