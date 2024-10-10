<script>
    import "../global.css";
    import Header from "./Header.svelte";
    import Footer from "./Footer.svelte";

    import oysterAndKnife from "$lib/oysterAndKnife.webp";
    import localPeople from "$lib/localPeople.webp";
    import visionOne from "$lib/visionOne.webp";
    import visionTwo from "$lib/visionTwo.webp";
</script>

<div class="container">
    <Header/>

    <div class="sectionTwo">
        <div class="partOne">
            <img src={oysterAndKnife} alt="Oyster knife sitting next to opened oysters"/>
            <h1>Local Seafood</h1>
        </div>

        <div class="partTwo">
            <img src={localPeople} alt="Two people smiling behind cooking ingredients"/>
            <h1>...from Good Local People</h1>
        </div>
    </div>

    <div class="video">
        <iframe loading="lazy" width="560" height="315" src="https://www.youtube-nocookie.com/embed/fJ6-nebvkeI?si=vkyRA5r90UBQ8IZn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>

    <div class="vision">
        <img src={visionTwo} alt="Man holding a fish">
        <div class="visionText">
            <h1>Our Vision</h1>
            <p>We want to be the leader in providing fresh, local seafood with exceptional customer service. We are a family owned business specializing in retail and wholesale seafood sales. We want our fish to be on the menu of your favorite local seafood restaurant. We want our customers to have the best possible experience so that they will tell their friends.</p>
        </div>
        <img src={visionOne} alt="Man holding fish in front of sign on building">
    </div>

    <Footer/>
</div>

<style>
    .sectionTwo{
        color: white;
        padding: 35px;
        position: relative;
        height: 850px;
    }

    .sectionTwo h1{
        color: rgb(200, 200, 200);
        font-size: 48px;
    }

    .partOne{
        display: flex;
        flex-direction: column;
        align-items: center;
        position: absolute;
        top: 35px;
        left: 35px;
        width: 50%;
    }

    .partOne img{
        width: 100%;
    }

    .partTwo{
        display: flex;
        flex-direction: column;
        align-items: center;
        position: absolute;
        bottom: 35px;
        right: 35px;
    }

    .video{
        display: flex;
        justify-content: center;
        width: 100%;
        margin: 55px 0;
    }

    iframe{
        height: 500px;
        width: 750px;
    }

    .vision{
        display: flex;
        justify-content: space-around;
        align-items: center;
        color: rgb(200, 200, 200);
        padding-top: 55px;
        margin-bottom: 35px;
    }

    .vision h1{
        text-align: center;
        font-size: 58px;
        text-decoration: underline;
    }

    .vision p{
        font-size: 25px;
        width: 500px;
        text-align: justify;
    }

    .vision img{
        width: 350px;
    }

    @media screen and (max-width: 1300px){
        .sectionTwo{
            height: initial;
        }

        .partOne, .partTwo{
            position: static;
            width: 100%;
            text-align: center;
            margin: 25px 0;
        }

        .partOne img, .partTwo img{
            max-width: 100%;
        }
    }

    @media screen and (max-width: 750px){
        iframe{
            aspect-ratio: 16/9;
            height: auto;
            width: 100%;
        }
    }
</style>
