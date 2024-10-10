<script>
    import storeFront from "$lib/harrelsons1.webp";
</script>

<header>
    <img src={storeFront} alt="Harrelsons Storefront">
    <div class="imageCover"></div>

    <div class="menu">
        <h1>Harrelson's Seafood</h1>
        <h2>Fresh Fish Daily</h2>
        <h3>Directly from Local Fishermen</h3>
    </div>
</header>

<style>
    header{
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh; 
        width: 100%;
        position: relative;
    }

    img{
        width: 100%;
        height: 100%;
        object-fit: cover;
        position: absolute;
        top: 0;
        left: 0;
        z-index: -2;
    }

    .imageCover{
        height: 100%;
        width: 100%;
        position: absolute;
        top: 0;
        left: 0;
        z-index: -1;
        background: rgba(0, 0, 0, 0.5);
    }

    .menu{
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
        height: 100%;
        color: white;
    }

    .menu h1{
        font-size: 68px;
    }

    .menu h2{
        font-size: 48px;
    }

    .menu h3{
        font-size: 38px;
    }
</style>
