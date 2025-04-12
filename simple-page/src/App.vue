<template>
    <header>
        <AppHeader />
    </header>
    <main>
        <AppHero />
    </main>
</template>

<script>
    import AppHeader from "./components/AppHeader.vue";
    import AppHero from "./components/AppHero.vue";

    export default {
    name: "App",
    components: {
    AppHeader,
    AppHero,
    },
    };
</script>
