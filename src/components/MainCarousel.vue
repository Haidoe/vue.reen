<template>
    <section class="slider">
			<div class="slider-container">
				<div class="slider-content">
					<p class="header"> Hi, I'm a developer </p>
					<p>
						Created this online portfolio with the professionally and lovingly designed REEN website template. 
                    </p>
					<button>GET STARTED NOW</button>
				</div>
			</div>
		</section>
</template>

<style scoped>
    section.slider {
        height: 880px;
        width: 100%;
        margin: 0;
        padding: 0;
        background: url("../assets/images/carousel/carousel-1.png") no-repeat;
        background-size: cover;
    }

    .slider .slider-container {
        width: 70%;
        height: inherit;
        padding: 0;
        margin: 0 auto;
        display: flex;
        justify-content: center;
        align-items: center;
        max-width: 1366px;
    }

    .slider .slider-container .slider-content {
        text-align: center;
        width: 60%;
        margin: auto;	
    }

    .slider .slider-container .slider-content p.header {
        font-size: 50pt;
        font-family: 'tahoma';
        color: #FFF;
        text-transform: uppercase;
        margin: 0;
        font-weight: bold;
    }

    .slider .slider-container .slider-content p {
        font-size: 18pt;
        font-family: "Source Sans Pro";
        color:#A3B1BF;
        margin: 5px 0;
    }

    .slider .slider-container .slider-content button {
        color: #FFF;
        height: 50px;
        width: 250px;
        display: flex;
        justify-content: center;
        align-items: center;
        background: #00BC9C;
        border: none;
        margin: 10px auto;
        border-radius: 5px;
        font-size: 10pt;
        font-family: "tahoma";
        font-weight: bold;
        margin-top: 30px;
    }

    .slider .slider-container .slider-content button:hover {
        cursor: pointer;
        background: #17A78B;
    }
</style>
