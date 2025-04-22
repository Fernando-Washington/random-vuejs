<template>
  <header>
    <Navbar />
  </header>
  <main>
    <MainTeste />
    <section class="flex p-10 align-center justify-center p-10px">
      <Timer />
    </section>
  </main>
</template>

<script>
import MainTeste from "./components/MainTeste.vue";
import Navbar from "./components/Navbar.vue";
import Timer from "./components/Timer.vue";

export default {
  components: {
    Navbar,
    MainTeste,
    Timer,
  },
};
</script>
