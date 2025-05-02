<script>
    import { onMount } from 'svelte';

    onMount(() => {
        console.log("Home page loaded");
    });
</script>

<div class="background">
    <div class="text">
        <h1>CONTACT ME</h1>
    </div>
    <div class="email">
        <h1>EMAIL</h1>
        <p>aleks.skarzycka@gmail.com</p>
    </div>
    <div class="phone">
        <h1>PERSONAL PHONE</h1>
        <p>+353 089 203 7473</p>
    </div>
</div>

<style>
    h1 { color: #1d003f; }
    p { color: #1d003f;
        font-size: 25px; }
    .background {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        background-image: url('$lib/img/portfolioBG.png');
        background-size: cover;
        height: 90vh;
        width: 100%; }
    .text { 
        background-color: rgba(212, 255, 0, 0.7);
        border-radius: 15px; 
        width: 500px;
        padding: 1%;
        margin: 1%; }
    .email { 
        background-color: rgba(212, 255, 0, 0.7);
        border-radius: 15px; 
        width: 500px;
        padding: 1%;
        margin: 1%; }
    .phone { 
        background-color: rgba(212, 255, 0, 0.7);
        border-radius: 15px;
        width: 500px; 
        padding: 1%;
        margin: 1%; }
</style>