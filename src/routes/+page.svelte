<script>
    import "../global.css";
    import Header from "./Header.svelte";

    import oysterAndKnife from "$lib/oysterAndKnife.webp";
    import localPeople from "$lib/localPeople.webp";
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
</div>

<style>
    .sectionTwo{
        background: rgb(0, 0, 25);
        color: white;
    }

    .sectionTwo h1{
        color: white;
        font-size: 48px;
    }

    .sectionTwo img{
        width: 35%;
    }

    .partOne{
        margin: 35px;
    }
</style>
