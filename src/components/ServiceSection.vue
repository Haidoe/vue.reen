<template>
    <section class="services">
        <div class="services-container">
            
            <div class="upper-content">
                <h1>
                    Beautiful. Clean. Responsive.
                </h1>
                <p>
                    REEN is a high-quality solution for those who want a beautiful website in no time. It's fully responsive and will adapt itself to any mobile device. iPad, iPhone, Android, it doesn't matter. Your content will always looks its absolute best.
                </p>
            </div>

            <div class="lower-content">
                <div>
                    <span id="passion"></span>
                    <aside>
                        <h3> Passion </h3>
                        <p> Magnis modipsae que lib voloratati andigen daepeditem quiate re porem aut labor. Laceaque quiae sitiorem rest non restibusaes maio es dem tumquam core posae volor remped modis volor.</p>
                    </aside>
                </div>
                
                <div >
                    <span id="creativity"></span>
                    <aside>
                        <h3> Creativity </h3>
                        <p>Magnis modipsae que lib voloratati andigen daepeditem quiate re porem aut labor. Laceaque quiae sitiorem rest non restibusaes maio es dem tumquam core posae volor remped modis volor.</p>
                    </aside>
                </div>

                <div>
                    <span id="quality"></span>
                    <aside>
                        <h3> Quality </h3>
                        <p> Magnis modipsae que lib voloratati andigen daepeditem quiate re porem aut labor. Laceaque quiae sitiorem rest non restibusaes maio es dem tumquam core posae volor remped modis volor.</p>
                    </aside>
                </div>
            </div>

        </div>
    </section>
</template>

<style scoped>
    .services {
        background: #FFF;
        width: 100%;
        height: 675px;
        color: #506A85;
    }

    .services-container {
        width: 70%;
        padding: 0 15px;
        margin: 0 auto;
        height: inherit;
        text-align: center;
        max-width: 1366px;
    }

    .services-container .upper-content {
        width: 70%;
        margin: 0 auto;
        position: relative;
        top: 120px;
    }

    .services-container .upper-content h1 {
        font-size: 35pt;
        margin-top: 0;
        margin-bottom: 5px;
        font-weight: normal;
    }

    .services-container .upper-content p {
        font-size: 17pt;
        font-family: "Source Sans Pro";
        color: #73879C;
        line-height: 1.5em;
    }

    .services-container .lower-content {
        position: relative;
        top: 140px;
        height: 200px;
        text-align: left;
    }

    .services-container .lower-content div {
        width: 33%;
        display: inline-block;
        height: inherit;
    }

    .services-container .lower-content div span {
        display: inline-block;
        width: 70px;
        height: 80px;
        background: url("../assets/images/services-logo-sprites.png") no-repeat;
        /* float: left; */
    }

    span#passion {
        background-position: 4px 10px;
    }

    span#creativity {
        background-position: -87px 10px;
    }

    span#quality {
        background-position: -178px 10px;
    }

    .services-container .lower-content div aside {
        float: right;
        text-align: left;
        width: 300px;
        height: inherit;
    }

    .services-container .lower-content div aside p {
        font-family: "Source Sans Pro";
        width: 90%;
    }

</style>
