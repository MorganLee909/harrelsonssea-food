<script>
    import "../../global.css";

    import one from "$lib/gallery/one.webp";
    import two from "$lib/gallery/two.webp";
    import three from "$lib/gallery/three.webp";
    import four from "$lib/gallery/four.webp";
    import five from "$lib/gallery/five.webp";
    import six from "$lib/gallery/six.webp";
    import seven from "$lib/gallery/seven.webp";
    import eight from "$lib/gallery/eight.webp";
    import nine from "$lib/gallery/nine.webp";
    import ten from "$lib/gallery/ten.webp";
    import eleven from "$lib/gallery/eleven.webp";
    import twelve from "$lib/gallery/twelve.webp";
    import thirteen from "$lib/gallery/thirteen.webp";
    import fourteen from "$lib/gallery/fourteen.webp";
    import fifteen from "$lib/gallery/fifteen.webp";
    import sixteen from "$lib/gallery/sixteen.webp";
    import seventeen from "$lib/gallery/seventeen.webp";
    import eighteen from "$lib/gallery/eighteen.webp";
    import nineteen from "$lib/gallery/nineteen.webp";
    import twenty from "$lib/gallery/twenty.webp";
    import twentyOne from "$lib/gallery/twentyOne.webp";
    import twentyTwo from "$lib/gallery/twentyTwo.webp";
    import twentyThree from "$lib/gallery/twentyThree.webp";
    import twentyFour from "$lib/gallery/twentyFour.webp";
    import twentyFive from "$lib/gallery/twentyFive.webp";
    import twentySix from "$lib/gallery/twentySix.webp";
    import twentySeven from "$lib/gallery/twentySeven.webp";
    import twentyEight from "$lib/gallery/twentyEight.webp";
    import twentyNine from "$lib/gallery/twentyNine.webp";
    import thirty from "$lib/gallery/thirty.webp";
    import thirtyOne from "$lib/gallery/thirtyOne.webp";
    import thirtyTwo from "$lib/gallery/thirtyTwo.webp";

    const images = [one, two, three, four, five, six, seven, eight, nine, ten, eleven, twelve, thirteen, fourteen, fifteen, sixteen, seventeen, eighteen, nineteen, twenty, twentyOne, twentyTwo, twentyThree, twentyFour, twentyFive, twentySix, twentySeven, twentyEight, twentyNine, thirty, thirtyOne, thirtyTwo];
</script>

<header>
    <a class="home" href="/">Harrelson's Seafood</a>
</header>

<div class="container">
    {#each images as image}
        <img src={image} alt="Dynamic gallery content">
    {/each}
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

    .home{
        color: black;
        font-size: 30px;
        text-decoration: none;
    }

    .container{
        display: flex;
        justify-content: space-around;
        align-items: center;
        flex-wrap: wrap;
        padding-top: 60px;
    }

    img{
        max-height: 550px;
        max-width: 550px;
        min-height: 250px;
        min-width: 250px;
        margin: 35px;
        border: 2px solid white;
    }
</style>
