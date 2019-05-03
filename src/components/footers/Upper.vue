<template>
    <footer class="upper">
        <div class="container">
            
            <div>
                <h3> WHO WE ARE </h3>
                <img src="../../assets/images/footer/footer-logo.png">
                <p>Magnis modipsae voloratati andigen daepeditem quiate re porem que aut labor. Laceaque eictemperum quiae sitiorem rest non restibusaes maio es dem tumquam.</p>
                <b> 
                    More about us 
                    <font-awesome-icon icon="arrow-right"></font-awesome-icon>
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
                    <font-awesome-icon icon="map-marker-alt"></font-awesome-icon>
                    Muntinlupa City, Philippines
                </p>
                
                <p>
                    <font-awesome-icon icon="mobile-alt"></font-awesome-icon>
                    +00 (123) 45678 90
                </p>
                
                <p>
                    <font-awesome-icon icon="envelope"></font-awesome-icon>
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

<style lang="sass" scoped>
    .upper 
        background: #2F4052
        height: auto

        .container
            display: flex
            align-items: flex-start
            justify-content: center
            padding: 40px 15px
            
            @media (max-width: 1024px)
                flex-wrap: wrap
                padding: 20px 15px
            
            svg
                margin-right: 10px
                margin-left: 10px
            div
                text-align: left
                padding: 5px
                color: #FFF
                flex-basis: 25%
                
                @media (max-width: 1024px)
                    flex-basis: 45%
                    margin: 15px 0
                    padding: 10px

                @media (max-width: 800px)
                    flex-basis: 90%
                    text-align: center

                h3 
                    font-family: "Tahoma"
                    font-size: 16pt
                    margin-top: 0
    
                p
                    font-size: 14pt
                    color: #A3B1BF
                
                b 
                    font-size: 15pt
                    color: A3B1BF

                figure 
                    margin: 0
                    padding: 0

                    img
                        height: auto
                        width: 147px
                        cursor: pointer
                        margin-left: 3px
    

                form 
                    display: flex

                    .subscribe 
                        background-color: #4E5C6C
                        border: none
                        height: 40px
                        border-top-left-radius: 5px
                        border-bottom-left-radius: 5px
                        flex-grow:2
                        padding-left: 15px
                        color: #A3B1BF
                        font-size: 13pt
    

                        &::placeholder 
                            color: #A3B1BF
                            font-family: "Source Sans Pro"
                            padding-top: 5px
                            font-size: 13pt

                    button 
                        color: #FFF
                        background-color: #00BC9C
                        border: none
                        border-top-right-radius: 5px
                        border-bottom-right-radius: 5px
                        height: 42px
                        font-weight: bold
                        cursor: pointer
                        padding: 2px 10px
                        &:hover
                            :background: #17A78B
    
</style>
