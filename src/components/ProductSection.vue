<template>
    <section class="latest-works">
        <div class="latest-works-container">
            <div class="title">
                <h1>Check out our latest works</h1>
                <p>Magnis modipsae que volorati andigen daeped tern quiate re porem aut labor</p>
            </div>

            <div class="work-list">
                
                <figure class="left">
                    <img src="../assets/images/product/work-1.png" alt="Latest Work Photo">
                    <figcaption>
                        <h3> Grand Motel gets an identity brushup </h3>
                        <p> Identity </p>
                    </figcaption>
                </figure>

                <figure class="right">
                    <img src="../assets/images/product/work-2.png" alt="Latest Work Photo">
                    <figcaption>
                        <h3> Fresh branding for creative startup </h3>
                        <p> Identity </p>
                    </figcaption>
                </figure>

            </div>

            <div class="work-carousel">
                <img src="../assets/images/product/work-carousel-1.png">
                <img src="../assets/images/product/work-carousel-2.png">
                <img src="../assets/images/product/work-carousel-3.png">
                <img src="../assets/images/product/work-carousel-4.png">
                
                <div class="carousel-button">
                    <!-- <span class="left-nav"></span> -->
                    <span class="blue-dot"></span>
                    <span class="green-dot"></span>
                    <span class="blue-dot"></span>
                    <!-- <span class="right-nav"></span>	-->
                </div>
            </div>
        </div>
    </section>
</template>


<style scoped>
    .latest-works {
        height: 1270px;
        width: 100%;
        background: #F2F5F7;
    }

    .latest-works-container {
        color: #506A85;
        width: 70%;
        margin: 0 auto;
    }

    .latest-works-container .title {
        position: relative;
        top: 130px;
        text-align: center;
    }

    .latest-works-container .title h1 {
        font-size: 32pt;
        font-family: "Tahoma";
        margin: 0;
    }

    .latest-works-container .title p {
        color: #73879C;
        font-size: 18pt;
    }

    .latest-works-container .work-list {
        position: relative;
        top: 150px;
        height: 500px;
        box-sizing: border-box;
        width: 90%;
        margin: 0 auto;
        text-align: center;
    }

    .latest-works-container .work-list figure {
        display: inline-block;
        height: 500px;
        box-sizing: content-box;
        text-align: center;
        margin: 0 15px;
    }

    .latest-works-container .work-list figure:hover {
        cursor: pointer;
    }

    .latest-works-container .work-list figure img {
        width: 565px;
        height: auto;
    }

    .latest-works-container .work-list figure figcaption {
        background: #FFF;
        height: 110px;
        position: relative;
        top: -5px;
        padding-top: 30px;
        box-sizing: border-box;
        border: 3px solid #E6E9ED;
        border-top-style: none;
    }

    .latest-works-container .work-list figure figcaption h3,
    .latest-works-container .work-list figure figcaption p {
        padding: 0;
        margin: 0;
    }

    .latest-works-container .work-carousel {
        clear: both;
        position: relative;
        top: 220px;
        width: 90%;
        margin: 0 auto;
        text-align: center;
    }

    .latest-works-container .work-carousel img {
        margin: 0 10px;
    }

    .latest-works-container .work-carousel .carousel-button {
        height: 30px;
        width: 100%;
        margin-top: 30px;
    }

    .latest-works-container .work-carousel .carousel-button span {
        display: inline-block;
        height: 20px;
        width: 20px;
        background: url("../assets/images/product/work-courasel-nav-sprite.png") no-repeat;
    }

    .latest-works-container .work-carousel .carousel-button span {
        cursor: pointer;
    }

    .latest-works-container .work-carousel .carousel-button span.blue-dot {
        margin: 5px 0;
        background-position: -42px -5px;
    }

    .latest-works-container .work-carousel .carousel-button span.green-dot {
        margin: 5px 0;
        background-position: -67px -5px;
    }

    .latest-works-container .work-carousel .carousel-button span.green-dot:hover {
        cursor: default;	
    }

    .latest-works-container .work-carousel .carousel-button span.left-nav, 
    .latest-works-container .work-carousel .carousel-button span.right-nav {
        width: 30px;
        height: 30px;
    }

    .latest-works-container .work-carousel .carousel-button span.right-nav {
        background-position: -125px 0 ;
    }
</style>
