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

        <div class="links">
            <a href="/menu" class="menuLink">
                <p>Menu</p> 
                <svg width="38px" height="38px" stroke-width="1.5" viewBox="0 0 24 24" fill="none" color="#000000">
                    <path d="M9 6L15 12L9 18" stroke="#000000" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path>
                </svg>
            </a>
            <a href="/gallery" class="menuLink gallery">
                <p>Gallery</p>
                <svg width="38px" height="38px" stroke-width="1.5" viewBox="0 0 24 24" fill="none" color="#000000">
                    <path d="M9 6L15 12L9 18" stroke="#000000" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path>
                </svg>
            </a>
        </div>
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

    .links{
        display: flex;
        flex-direction: column;
        position: absolute;
        top: 35px;
        right: 35px;
    }

    .menuLink{
        display: flex;
        justify-content: flex-end;
        align-items: center;
        color: black;
        background: rgb(200, 200, 200);
        text-decoration: none;
        padding: 5px 5px 5px 15px;;
        border-radius: 5px;
        font-size: 28px;
        width: 160px;
        margin: 10px 0;
    }

    .menuLink:hover{
        background: rgb(150, 150, 150);
    }

    .gallery{
        top: 95px;
    }

    h1, h2, h3{
        text-align: center;
    }

    h1{
        font-size: 68px;
    }

    h2{
        font-size: 48px;
    }

    h3{
        font-size: 38px;
    }

    @media screen and (max-width: 1100px){
        .links{
            flex-direction: row;
            justify-content: space-around;
            width: 100%;
            right: 0;
        }

        .menuLink{
            margin: 0;
        }
    }

    @media screen and (max-width: 600px){
        .menu h1{
            font-size: 58px;
        }
    }
</style>
