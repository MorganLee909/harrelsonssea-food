<script>
    import "../../global.css";

    import shrimp from "$lib/menu/shrimp.webp"
    import grouper from "$lib/menu/grouper.webp";
    import snapper from "$lib/menu/snapper.webp";
    import tuna from "$lib/menu/tuna.webp";
    import oysters from "$lib/menu/oysters.webp";
    import baconScallops from "$lib/menu/baconScallops.webp";
    import blueCrab from "$lib/menu/blueCrab.webp";
    import boil from "$lib/menu/boil.webp";
    import conchFritters from "$lib/menu/conchFritters.webp";
    import crabCakes from "$lib/menu/crabCakes.webp";
    import flounder from "$lib/menu/flounder.webp";
    import hog from "$lib/menu/hog.webp";
    import mahi from "$lib/menu/mahi.webp";
    import salmon from "$lib/menu/salmon.webp";
    import trigger from "$lib/menu/trigger.webp";
    import tylersOysters from "$lib/menu/tylersOysters.webp";

    import sheCrabSoup from "$lib/menu/sheCrabSoup.webp";
    import clamChowder from "$lib/menu/clamChowder.webp";

    import remoulade from "$lib/menu/remoulade.webp";
    import cocktailSauce from "$lib/menu/cocktailSauce.webp";
    import aioli from "$lib/menu/aioli.webp";
    import blueCrabDip from "$lib/menu/blueCrabDip.webp";

    import fishSkin from "$lib/menu/fishSkin.webp";
    import anchorPins from "$lib/menu/anchorPins.webp";
    import shirts from "$lib/menu/shirts.webp";
    import seafoodBasket from "$lib/menu/seafoodBasket.webp";
</script>

<svelte:head>
    <title>Menu | Harrelson's Seafood</title>
</svelte:head>

<header>
    <a class="home" href="/">Harrelson's Seafood</a>
</header>

<div class="container">
    <div class="section seafood">
        <h1>Retail Seafood</h1>

        <div class="items">
            <div class="item">
                <img src={shrimp} alt="Seasoned shrimp">
                <p class="name">Fresh Local Shrimp</p>
                <p class="note">Buy 5 lbs or more of any size and receive $1.00 off per lb.</p>
            </div>

            <div class="item">
                <img src={grouper} alt="Close up of grouper meat">
                <p class="name">Fresh Local Grouper</p>
            </div>

            <div class="item">
                <img src={snapper} alt="Snappers on ice">
                <p class="name">Snapper</p>
            </div>

            <div class="item">
                <img src={tuna} alt="Tuna steaks beside a knife">
                <p class="name">Yellow-Fin Tuna</p>
                <p class="note">Sushi-Grade Tuna</p>
            </div>

            <div class="item">
                <img src={oysters} alt="Oysters in the shell">
                <p class="name">Local Oysters</p>
                <p class="note">Our Local Oysters are available October through April every year. Reservations are recommended.</p>
            </div>

            <div class="item">
                <img src={boil} alt="A pile of vegetables and shrimp">
                <p class="name">Low Country Boil</p>
                <p class="note">We sell Homemade Low Country Boil Bags. Take it home, add it to boiling water for 8 minutes and you're ready to eat. Serves 2.</p>
            </div>

            <div class="item">
                <img src={trigger} alt="Trigger fish on a table">
                <p class="name">Trigger Fish</p>
            </div>

            <div class="item">
                <img src={hog} alt="Hog Fish on ice">
                <p class="name">Hog Fish</p>
            </div>

            <div class="item">
                <img src={flounder} alt="Woman holding up a flounder">
                <p class="name">Flounder</p>
            </div>

            <div class="item">
                <img src={mahi} alt="Several Mahi-Mahi on ice">
                <p class="name">Mahi-Mahi</p>
            </div>

            <div class="item">
                <img src={salmon} alt="Salmon on a cutting board with lemons">
                <p class="name">Salmon</p>
            </div>

            <div class="item">
                <img src={blueCrab} alt="Blue crabs in a basket">
                <p class="name">Live Blue Crab</p>
                <p class="note">Please call for availability and price. Reservations are recommended.</p>
            </div>

            <div class="item">
                <img src={baconScallops} alt="Bacon wrapped scallops on a kebab">
                <p class="name">Bacon Wrap Scallops</p>
            </div>

            <div class="item">
                <img src={conchFritters} alt="Collection of conch fritters">
                <p class="name">Homemade Conch Fritters</p>
                <p class="note">Great paired with our Homemade Key Lime Chipotle Aioli</p>
            </div>

            <div class="item">
                <img src={crabCakes} alt="Several crab cakes with dressings">
                <p class="name">Crab Cakes</p>
                <p class="note">Crab Cake Lady Crab Cakes great paired with our Homemade Sweet Vidalia Fire Roasted Red Pepper Remoulade Sauce. Sold individually or by the dozen.</p>
            </div>

            <div class="item">
                <img src={tylersOysters} alt="Oysters on a grill">
                <p class="name">Tyler's Char-Grilled Oysters</p>
                <p class="note">Select oysters covered with an abundance of different butters and cheeses. Perfect for the grill.</p>
            </div>
        </div>
    </div>

    <div class="section soups">
        <h1>Soups</h1>

        <div class="items">
            <div class="item">
                <img loading="lazy" src={sheCrabSoup} alt="She Crab soup with garnish">
                <p class="name">She Crab Soup</p>
                <p class="note">Our homemade She Crab Soup is packaged by the pint. Great with our hand-made crab cakes</p>
            </div>

            <div class="item">
                <img src={clamChowder} alt="Clam Chowder is a bowl" loading="lazy">
                <p class="name">Homemade Clam Chowder</p>
            </div>
        </div>
    </div>

    <div class="section sauces">
        <h1>Homemade Sauces</h1>

        <div class="items">
            <div class="item">
                <img src={remoulade} alt="Top of remoulade sauce container" loading="lazy">
                <p class="name">Remoulade Sauce</p>
                <p class="note">Sweet Vidalia Fire-Roasted Red Pepper Remoulade Sauce. A must for our crab cakes and great paired with the fish of your choice.</p>
            </div>

            <div class="item">
                <img src={cocktailSauce} alt="Top of cocktail sauce container" loading="lazy">
                <p class="name">Homemade Cocktail Sauce</p>
                <p class="note">Our Homemade Cocktail Sauce. Simply put the BEST on the market!</p>
            </div>

            <div class="item">
                <img src={aioli} alt="Top of Key Lime chipotle Aioli sauce container" loading="lazy">
                <p class="name">Key Lime Chipotle Aioli</p>
                <p class="note">A new addition created for our Homemade Conch Fritters. Great on everything.</p>
            </div>

            <div class="item">
                <img src={blueCrabDip} alt="Top of Blue Crab Dip sauce container" loading="lazy">
                <p class="name">Blue Crab Dip</p>
            </div>
        </div>
    </div>

    <div class="section other">
        <h1>Other</h1>

        <div class="items">
            <div class="item">
                <img src={fishSkin} alt="Container with packages of fish skins" loading="lazy">
                <p class="name">Fish Skin Pet Snacks</p>
                <p class="note">As animal lovers, we have been giving these to our dogs for years. Now you can too. No preservatives. As we harvest our fish fillets, the skins are prepared for your pet friends.</p>
            </div>

            <div class="item">
                <img src={anchorPins} alt="Two anchor pins" loading="lazy">
                <p class="name">Shallow Water Anchor Pins</p>
                <p class="note">Ultra quiet, super strong, long lasting. A must for sneaking up on those finicky Winter RedFish.</p>
            </div>

            <div class="item">
                <img src={shirts} alt="Shirt design of palm tree" loading="lazy">
                <p class="name">T-Shirts</p>
                <p class="note">Our interpretation of the South Carolina state flag has quickly become a locals favorite. Short and long sleeve available, many sizes and colors to choose from.</p>
            </div>

            <div class="item">
                <img src={seafoodBasket} alt="Various seafood dishes" loading="lazy">
                <p class="name">Captain's Seafood Basket</p>
                <p class="note">Our Captains's Seafood Basket combines 2 7oz lobster tails, 5 lbs of large shrimp, 1 Low-country Boil Bag, 1 Bacon Wrap Scallop and a reusable cooler.</p>
            </div>
        </div>
    </div>
</div>

<style>
    header{
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0 35px;
        height: 50px;
        width: 100vw;
        background: rgb(150, 150, 150);
        position: fixed;
    }

    header a{
        color: black;
    }

    .home{
        font-size: 30px;
        text-decoration: none;
        color: black;
    }

    .container{
        color: rgb(200, 200, 200);
    }

    .section{
        padding-top: 75px;
    }

    .section h1{
        font-size: 38px;
        text-align: center;
        border-bottom: 1px solid white;
    }

    .items{
        display: flex;
        justify-content: space-around;
        flex-wrap: wrap;
        padding: 35px;
    }

    .item{
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 200px;
        margin: 25px;
    }

    .item .name{
        font-size: 16px;
        border-bottom: 1px solid white;
        width: 100%;
        text-align: center;
        padding: 15px 0;
    }

    .item .note{
        font-size: 14px;
        text-align: center;
    }

    .item img{
        height: 200px;
        width: 200px;
        border-radius: 25px;
        border: 2px solid white;
    }

    .sauces .item img{
        border-radius: 50%;
    }

    @media screen and (max-width: 600px){
        .home{
            font-size: 22px;
        }

        .item{
            width: 125px;
        }

        .item img {
            height: 125px;
            width: 125px;
        }
    }
</style>
