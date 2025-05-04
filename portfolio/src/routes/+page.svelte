<script>
    import { base } from '$app/paths';
</script>

<div class="background">
    <div class="text">
        <h1>Aleksandra Skarzycka</h1>
        <p>My Portfolio</p>
    </div>
</div>

<style>
    h1 { color: #1d003f;
         font-size: 50px; }
    p { font-size: 35px;
        color: #1d003f; }
    .background {
        display: flex;
        align-items: center;
        justify-content: center;
        background-image: url('/img/portfolioBG.png');
        background-size: cover;
        height: 90vh;
        width: 100%; }
    .text { 
        background-color: rgba(212, 255, 0, 0.7);
        border-radius: 15px; 
        width: 600px; 
        padding: 1%;}
</style>