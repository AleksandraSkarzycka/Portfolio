<script>
    import { base } from '$app/paths';
</script>

<div class="background">
    <div class="about">
        <h1>ABOUT ME</h1>
    </div>
    <div class="info">
        <p>My name is Aleksandra Skarzycka. I am 20 years old, born on the 6th of 
            April 2005 in Poland, but living in Ireland since 9 months old. I currently
            live in Carlow. <br> <br>
            I am studing Interactive Digital Art and Design at SETU Carlow, graduating in 2027, and I hope to
            grow and better my skills. I really hope to become great at art both traditionally
            and digitally so I could become a concept artist for shows/games. I would also really
            like to improve on my coding skills so I can continue to build awesome websites. <br> <br>
            I currently work at KFC Carlow and hope that in the future that job changes
            to working with creative companies looking for a concept artist or someone who can
            build websites! <br> <br>

            <a href="{base}/AleksandraSkarzycka_CV.pdf" download>MY CV</a>
        </p>
    </div>
</div>

<style>
    h1 { color: #1d003f; }
    p { color:#1d003f;
        font-size: 24px;}
    .background {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: start;
        background-image: url('/img/portfolioBlankBG.png');
        background-size: cover;
        height: 90vh;
        width: 100%; }
    .about { 
        background-color: rgba(212, 255, 0, 0.7);
        border-radius: 15px; 
        width: 500px;
        padding: 1%;
        margin: 1%; }
    .info { 
        background-color: rgba(212, 255, 0, 0.7);
        border-radius: 15px; 
        width: 700px;
        padding: 1%;
        margin: 1%; }
</style>