<script>
    import Header from "../components/header.svelte";
    import Footer from "../components/footer.svelte";
</script>

<Header />

<main>
    <slot />
</main>

<Footer />

<style lang="scss">
    @import "../styles.scss";
</style>
