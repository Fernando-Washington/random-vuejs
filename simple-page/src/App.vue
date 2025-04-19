<template>
  <header>
    <AppHeader />
  </header>
  <section>
    <AppHero />
    <AppInfo />
  </section>
  <section>
    <InfoBanner title1="Introduction" title2="To hydra vr" mainText="Vitae sapien pellentesque habitant morbi tristique senectus et netus et. Feugiat nibh sed pulvinar proin gravida hendrerit lectus. Mi sit amet mauris commodo quis imperdiet massa tincidunt nunc. Viverra aliquet eget sit amet tellus. Ornare lectus sit amet est placerat in. Lectus magna fringilla urna porttitor rhoncus vitae."/>
    <AboutHydra />
    <InfoBanner title1="Why build" title2="With hydra?" mainText="Vitae sapien pellentesque habitant morbi tristique senectus et netus et. Feugiat nibh sed pulvinar proin gravida hendrerit lectus. Mi sit amet mauris commodo quis imperdiet massa tincidunt nunc. Viverra aliquet eget sit amet tellus. Ornare lectus sit amet est placerat in. Lectus magna fringilla urna porttitor rhoncus vitae."/>
  </section>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import AppHero from "./components/AppHero.vue";
import AppInfo from "./components/AppInfo.vue";
import InfoBanner from "./components/InfoBanner.vue";
import AboutHydra from "./components/AboutHydra.vue";

export default {
  name: "App",
  components: {
    AppHeader,
    AppHero,
    AppInfo,
    InfoBanner,
    AboutHydra,
  },
};
</script>
