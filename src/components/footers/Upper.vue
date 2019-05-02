<template>
    <footer class="upper">
        <div class="upper-footer-container">
            
            <div>
                <h3> WHO WE ARE </h3>
                <img src="../../assets/images/footer/footer-logo.png">
                <p>Magnis modipsae voloratati andigen daepeditem quiate re porem que aut labor. Laceaque eictemperum quiae sitiorem rest non restibusaes maio es dem tumquam.</p>
                <b> 
                    More about us 
                    <span class="footer-icon" id="right-arrow"></span>
                </b>
            </div>
            
            <div>
                <h3> LATEST WORKS </h3>
                <figure>
                    <img src="../../assets/images/footer/footer-work-1.png">
                    <img src="../../assets/images/footer/footer-work-2.png">
                    <img src="../../assets/images/footer/footer-work-3.png">
                    <img src="../../assets/images/footer/footer-work-4.png">
                </figure>
            </div>

            <div>
                <h3> GET IN TOUCH </h3>
                <p> Doloreiur quia commolu ptatemp dolupta oreprerum tibusam eumenis et consent accullignis dentibea autem inisita. </p>
                <p>
                    <span class="footer-icon" id="location"></span> 
                    Muntinlupa City, Philippines
                </p>
                
                <p>
                    <span class="footer-icon" id="phone"></span>
                    +00 (123) 45678 90
                </p>
                
                <p>
                    <span class="footer-icon" id="message"></span>
                    haidren.amalia@gmail.com
                </p>
            </div>
            
            <div>
                <h3> FREE UPDATES </h3>	
                <p>
                    Conecus iure posae volor remped modis aut lor volor accabora incim resto explabo.
                </p>

                <form>
                    <input type="name" class="subscribe" placeholder="Enter your email address">
                    <button> SUBSCRIBE </button>
                </form>
            </div>
        
        </div>
    </footer>
</template>

<style scoped>
    footer.upper {
        background: #2F4052;
        height: 365px;
    }

    .upper-footer-container {
        width: 70%;
        box-sizing: border-box;
        text-align: center;
        margin: 0 auto;
        font-family: "Source Sans Pro";
        display: flex;
        align-items: flex-start;
        justify-content: center;
        max-width: 1366px;
    }

    .upper-footer-container div {
        box-sizing: border-box;
        width: calc(100%/4);
        position: relative;
        top: 40px;
        text-align: left;
        color: #FFF;
        margin: 0 15px;
    }
    .upper-footer-container div h3 {
        font-family: "Tahoma";
        font-size: 16pt;
        margin-top: 0;
    }

    .upper-footer-container .footer-icon {
        display: inline-block;
        background: url("../../assets/images/footer/footer-icon-sprite.png") no-repeat;
        margin-right: 10px;
    }

    .upper-footer-container #right-arrow {
        background-position: 0 -64px;
        height: 9px;
        width: 10px;
    }

    .upper-footer-container #location {
        background-position: 0 3px;
        height: 15px;
        width: 11px;
    }

    .upper-footer-container #message {
        background-position: 0 -43px;
        height: 12px;
        width: 11px;
    }

    .upper-footer-container #phone {
        background-position: 0 -17px;
        height: 17px;
        width: 11px;
    }

    .upper-footer-container div p {
        font-size: 14pt;
        color: #A3B1BF;
    }

    .upper-footer-container div b {
        font-size: 15pt;
        color: #A3B1BF;
    }

    .upper-footer-container div figure {
        margin: 0;
        padding: 0;
    }

    .upper-footer-container div figure img {
        height: auto;
        width: 147px;
        cursor: pointer;
    }

    .upper-footer-container form {
        display: flex;
    }

    .upper-footer-container form .subscribe {
        background-color: #4E5C6C;
        border: none;
        height: 40px;
        border-radius: 5px;
        flex-grow:2;
        padding-left: 15px;
        color: #A3B1BF;
        font-size: 13pt;
        font-family: "Source Sans Pro";
    }

    .upper-footer-container form .subscribe::placeholder {
        color: #A3B1BF;
        font-family: "Source Sans Pro";
        padding-top: 5px;
        font-size: 13pt;

    }

    .upper-footer-container form button {
        color: #FFF;
        background-color: #00BC9C;
        border: none;
        border-radius: 5px;
        position: absolute;
        right: 10px;
        height: 30px;
        margin-top: 5px;
        font-family: "Source Sans Pro";
        font-weight: bold;
        cursor: pointer;
        padding: 2px 10px;
    }

    .upper-footer-container form button:hover {
        background: #17A78B;
    }
</style>
