<script>
    import Carousel from "../components/carousel.svelte";

    const images = [
        {
            id: "anh1",
            path: "../src/public/anh1.jpg",
        },
        {
            id: "anh2",
            path: "../src/public/anh2.png",
        },
        {
            id: "anh3",
            path: "../src/public/anh3.png",
        },
    ];
</script>

<svelte:head>
    <title>Trường đại học Đà Lạt</title>
</svelte:head>

<section class="flex flex-col items-center">
    <Carousel {images} imageWhidth={980} imageSpacing={15} />

    <slot />
</section>
