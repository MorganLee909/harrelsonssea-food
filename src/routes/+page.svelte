<script>
    import "../global.css";
    import Header from "./Header.svelte";
    import Footer from "./Footer.svelte";

    import oysterAndKnife from "$lib/oysterAndKnife.webp";
    import localPeople from "$lib/localPeople.webp";
    import visionOne from "$lib/visionOne.webp";
    import visionTwo from "$lib/visionTwo.webp";
</script>

<svelte:head>
    <title>Harrelson's Seafood</title>
</svelte:head>

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

    <div class="locations">
        <h1>2nd Location Now Open!</h1>

        <div class="location">
            <h2>Murrells Inlet</h2>
            <a href="https://www.google.com/maps/place/Harrelson's+Seafood+Market+Pawley's+Island/@33.4328599,-79.1382823,20.5z/data=!4m6!3m5!1s0x890031031f80315d:0x3b85f623e370b3ce!8m2!3d33.4330432!4d-79.1379417!16s%2Fg%2F11vycd4xft?entry=ttu&g_ep=EgoyMDI0MTAwOC4wIKXMDSoASAFQAw%3D%3D" target="_blank">
                4368 Highway 17 Business, Murrells Inlet, SC 29576
            </a>
            <a href="tel:+18436515707">(843) 651-5707</a>
            <table>
                <caption>Hours</caption>
                <tr>
                    <td>Sunday</td>
                    <td>9am - 6pm</td>
                </tr>
                <tr>
                    <td>Monday</td>
                    <td>8am - 7pm</td>
                </tr>
                <tr>
                    <td>Tuesday</td>
                    <td>8am - 7pm</td>
                </tr>
                <tr>
                    <td>Wednesday</td>
                    <td>8am - 7pm</td>
                </tr>
                <tr>
                    <td>Thursday</td>
                    <td>8am - 7pm</td>
                </tr>
                <tr>
                    <td>Friday</td>
                    <td>8am - 7pm</td>
                </tr>
                <tr>
                    <td>Saturday</td>
                    <td>8am - 7pm</td>
                </tr>
            </table>
        </div>

        <div class="location">
            <h2>Pawleys Island</h2>
            <a href="https://www.google.com/maps/place/Harrelson's+Seafood+Market+Pawley's+Island/@33.4328599,-79.1382823,20.5z/data=!4m6!3m5!1s0x890031031f80315d:0x3b85f623e370b3ce!8m2!3d33.4330432!4d-79.1379417!16s%2Fg%2F11vycd4xft?entry=ttu&g_ep=EgoyMDI0MTAwOC4wIKXMDSoASAFQAw%3D%3D" target="_blank">
                9752 Ocean Highway, Pawleys Island, SC 29585
            </a>
            <a href="tel:+8433140648">(843) 314-0648</a>
            <table>
                <caption>Hours</caption>
                <tr>
                    <td>Sunday</td>
                    <td>9am - 6pm</td>
                </tr>
                <tr>
                    <td>Monday</td>
                    <td>9am - 6pm</td>
                </tr>
                <tr>
                    <td>Tuesday</td>
                    <td>9am - 6pm</td>
                </tr>
                <tr>
                    <td>Wednesday</td>
                    <td>9am - 6pm</td>
                </tr>
                <tr>
                    <td>Thursday</td>
                    <td>9am - 6pm</td>
                </tr>
                <tr>
                    <td>Friday</td>
                    <td>9am - 6pm</td>
                </tr>
                <tr>
                    <td>Saturday</td>
                    <td>9am - 6pm</td>
                </tr>
            </table>
        </div>
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

    .locations{
        display: flex;
        justify-content: space-around;
        color: rgb(200, 200, 200);
        position: relative;
    }

    .locations h1{
        font-size: 58px;
        width: 100%;
        text-align: center;
        text-decoration: underline;
        position: absolute;
        top: 0;
        left: 0;
    }

    .location{
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: 100px 0 35px 0;
    }

    .location h2{
        font-size: 38px;
    }

    .location a{
        color: rgb(200, 200, 200);
        font-size: 22px;
        margin: 15px 0;
    }

    table{
        font-size: 18px;
        border-spacing: 35px 5px;
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

        .vision img{
            display: none;
        }
    }

    @media screen and (max-width: 1200px){
        .locations{
            flex-direction: column;
        }
    }

    @media screen and (max-width: 750px){
        iframe{
            aspect-ratio: 16/9;
            height: auto;
            width: 100%;
        }

        .vision p{
            width: initial;
            padding: 0 15px;
            font-size: 22px;
            line-height: 38px;
        }

        .locations h1{
            font-size: 38px;
        }

        .location{
            margin-top: 55px;
        }

        .location:nth-child(3){
            margin-top: 0;
        }
    }

    @media screen and (max-width: 600px){
        .location a{
            font-size: 18px;
            text-align: center;
        }

        .location:nth-child(2){
            margin-top: 115px;
        }

        table{
            font-size: 16px;
        }
    }
</style>
