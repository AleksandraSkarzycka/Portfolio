<script>
    import { onMount } from 'svelte';

    import greyCube from '$lib/img/cube_aleksandra.png';
    import redApple from '$lib/img/APPLE_RENDER_ALEKSANDRA.png';
    import mustangCar from '$lib/img/MUSTANG_RENDER_ALEKSANDRA.png';
    import fabricClose from '$lib/img/fabrictexture_closeup.png';
    import allTextures from '$lib/img/TEXTURES_DIGITAL_ALEKSANDRA.png';

    onMount(() => {
        console.log("Home page loaded");
    });
</script>

<div class="background">
    <div class="works">
        <h1>MY WORKS</h1>
    </div>
    <div class="layout">
        <img src='{greyCube}' alt="Grey 3D slightly chipped cube" style="width: 500px;">
        <img src='{redApple}' alt="Rendered red apple" style="width: 500px;">
        <img src='{mustangCar}' alt="Rendered red mustang" style="width: 500px;">
        <img src='{fabricClose}' alt="Close-up of rendered fabric texture" style="width: 500px;">
        <img src='{allTextures}' alt="Fabric, metal, cracked pavement, wooden planks, rain droplets, cobblestone, roof tiles, marble, grass and woven renders" style="width: 1004px;">
    </div>
    <div class="extras">
        <a href="$lib/img/PersonalArt.zip" download>Extra Personal Art</a>
    </div>
</div>

<style>
    h1 { color: #1d003f; }
    .background {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: start;
        background-image: url('$lib/img/portfolioBlankBG.png');
        background-size: cover;
        height: 500vh;
        width: 100%; }
    .works { 
        background-color: rgba(212, 255, 0, 0.7);
        border-radius: 15px; 
        width: 500px;
        padding: 1%;
        margin: 1%; }
</style>