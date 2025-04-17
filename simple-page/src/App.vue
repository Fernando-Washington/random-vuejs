<template>
    <header>
        <AppHeader />
    </header>
    <main>
        <AppHero />
    </main>
        <AppInfo />
</template>

<script>
    import AppHeader from "./components/AppHeader.vue";
    import AppHero from "./components/AppHero.vue";
    import AppInfo from "./components/AppInfo.vue";

    export default {
    name: "App",
    components: {
    AppHeader,
    AppHero,
    AppInfo,
    },
};
</script>