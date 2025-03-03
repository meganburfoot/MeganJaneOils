
<div class="page-layout">
    <div class="side-strip"></div>
    <div class="wrapper">
        <div class="container">
            <h1>Megan Jane Oil Painting</h1>
            <p class="description">
                I am an artist based in Takapuna, New Zealand. 
                <br>
                I specialize in oil paintings and offer commission services. 
                <br>
                If you are interested in a custom piece, please contact me at 021 130 4965.
            </p>
            
            <img src="/Mallorca2024.jpg" alt="Mallorca 2024" class="landscape" />
            <img src="/MontyPink.jpg" alt="Monty Pink" class="portrait" />
            <img src="/RockyPuppy.jpg" alt="Rocky Puppy" class="landscape" />
            <img src="/JacquiHair.jpg" alt="Jacqui Hair" class="portrait" />
            
            <div class="side-by-side">
                <img src="/KylieBlue.jpg" alt="Kylie Blue" class="half" />
                <img src="/MontyBlue.jpg" alt="Monty Blue" class="half" />
            </div>
            
            <img src="/QtownCottage.png" alt="Qtown Cottage" class="portrait" />
        </div>
    </div>
    <div class="side-strip"></div>
</div>

<style>
    body {
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        background-color: #FF6F61; /* Coral pink color */
    }

    .page-layout {
        display: grid;
        grid-template-columns: 1fr 4fr 1fr; /* Adjust the fractions to control the width of the pink strips */
        width: 100%;
        height: 100%;
    }

    .side-strip {
        background-color: #ffa7cf; /* Coral pink color */
    }

    .wrapper {
        background-color: white;
        padding: 20px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    h1 {
        color: #ff006a; /* Dark blue color */
		margin-bottom: 0px;
    }

    .description {
        color: #575355; /* Text color */
        font-size: 1.2em;
        margin-bottom: 20px;
        text-align: center;
    }

    img {
        border-radius: 5px;
    }

    .landscape {
        width: 80%;
    }

    .portrait {
        width: 60%;
    }

    .half {
        width: 48%;
    }

    .container {
        display: grid;
        justify-items: center;
        gap: 40px;
    }

    .side-by-side {
        display: flex;
        gap: 40px; /* Adjust the gap between the images as needed */
    }
</style>