<script>
    import Header from "../components/header.svelte";
    import Nav from "../components/nav.svelte";
    import Footer from "../components/footer.svelte";
    import Banners from "../components/banners.svelte";
    import "../app.css";
</script>

<Header />
<Nav />
<Footer />
<!-- <Banners/> -->

<slot />
