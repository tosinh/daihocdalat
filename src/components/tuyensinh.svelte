<script>
    const tsImages = [
        {
            id: "anh1",
            path: "../src/public/tuyensinh/anh1.jpg",
        },
        {
            id: "anh2",
            path: "../src/public/tuyensinh/anh2.png",
        },
        {
            id: "anh3",
            path: "../src/public/tuyensinh/anh3.png",
        },
        {
            id: "anh4",
            path: "../src/public/tuyensinh/anh4.png",
        },
    ];
</script>

<div>
    <span>Tuyển Sinh</span>
</div>
<div class="tuyensinh-image">
    {#each tsImages as image}
        <a href="#"><img src={image.path} alt={image.id} /></a>
    {/each}
</div>

<style>
    div {
        width: 980px;
    }
    div span {
        margin: 35px 0;
    }
    span {
        display: block;
        text-align: center;
        text-transform: uppercase;
        color: rgb(122, 162, 40);
        font-size: 24px;
        font-weight: 700;
        line-height: 42px;
        /* border-bottom: 1px solid rgb(122, 162, 40); */
    }
    .tuyensinh-image {
        display: flex;
        justify-content: space-around;
    }
    img {
        max-width: 268px;
        height: 250px;
    }
</style>
