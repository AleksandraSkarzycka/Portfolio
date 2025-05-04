<script>
    import { base } from '$app/paths';
</script>

<div class="background">
    <div class="works">
        <h1>MY WORKS</h1>
    </div>
    <div class="layout">
        <img src='{base}/img/cube_aleksandra.png' alt="Grey 3D slightly chipped cube" style="width: 500px;">
        <img src='{base}/img/APPLE_RENDER_ALEKSANDRA.png' alt="Rendered red apple" style="width: 500px;">
        <img src='{base}/img/MUSTANG_RENDER_ALEKSANDRA.png' alt="Rendered red mustang" style="width: 500px;">
        <img src='{base}/img/fabrictexture_closeup.png' alt="Close-up of rendered fabric texture" style="width: 500px;">
        <img src='{base}/img/TEXTURES_DIGITAL_ALEKSANDRA.png' alt="Fabric, metal, cracked pavement, wooden planks, rain droplets, cobblestone, roof tiles, marble, grass and woven renders" style="width: 1004px;">
    </div>
    <div class="extras">
        <a href="{base}/PixelArt.zip" download>Extra Pixel Art</a> <br>
        <a href="{base}/PersonalExtraArt.zip" download>Extra Personal Art</a>
    </div>
</div>

<style>
    h1 { color: #1d003f; }
    .background {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: start;
        background-image: url('/img/portfolioBlankBG.png');
        background-size: cover;
        height: 140vh;
        width: 100%; }
    .works { 
        background-color: rgba(212, 255, 0, 0.7);
        border-radius: 15px; 
        width: 500px;
        padding: 1%;
        margin: 1%; }
    .extras { 
        background-color: rgba(212, 255, 0, 0.7);
        border-radius: 15px; 
        width: 500px;
        padding: 1%;
        margin: 1%; }
</style>