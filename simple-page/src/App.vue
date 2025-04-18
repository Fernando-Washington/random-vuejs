<template>
    <header>
        <AppHeader />
    </header>
    <main>
        <AppHero />
    </main>
        <AppInfo />
        <InfoBanner />
        <AboutHydra />
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