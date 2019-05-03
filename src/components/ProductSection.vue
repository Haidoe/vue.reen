<template>
    <section>
        <div class="container">
            <div class="title">
                <h1>Check out our latest works</h1>
                <p>Magnis modipsae que volorati andigen daeped tern quiate re porem aut labor</p>
            </div>

            <div class="work-list">
                
                <figure>
                    <img src="../assets/images/product/work-1.png" alt="Latest Work Photo">
                    <figcaption>
                        <h3> Grand Motel gets an identity brushup </h3>
                        <p> Identity </p>
                    </figcaption>
                </figure>

                <figure>
                    <img src="../assets/images/product/work-2.png" alt="Latest Work Photo">
                    <figcaption>
                        <h3> Fresh branding for creative startup </h3>
                        <p> Identity </p>
                    </figcaption>
                </figure>

            </div>

            <div class="work-carousel">

                <div class="image-list">
                    <img src="../assets/images/product/work-carousel-1.png">
                    <img src="../assets/images/product/work-carousel-2.png">
                    <img src="../assets/images/product/work-carousel-3.png">
                    <img src="../assets/images/product/work-carousel-4.png">
                </div>
                
                <div class="carousel-button">
                    <!-- <span class="left-nav"></span> -->
                    <span class="blue-dot"></span>
                    <span class="green-dot"></span>
                    <span class="blue-dot"></span>
                    <!-- <span class="right-nav"></span>	 -->
                </div>
            </div>
        </div>
    </section>
</template>


<style lang="sass" scoped>
    section 
        height: auto
        padding: 100px 0
        background: #F2F5F7
        
        @media (max-width: 640px)
            padding: 50px 0
            
        .container
            display: flex
            flex-direction: column
            justify-content: center
            flex-wrap: no-wrap
            overflow: hidden
            
            .title 
                text-align: center
                margin-bottom: 30px
        
                h1 
                    font-size: 32pt
                    font-family: "Tahoma"
                    margin: 0

                    @media (max-width: 1024px)
                        font-size: 24pt

                    @media (max-width: 640px)
                        font-size: 20pt
                p 
                    color: #73879C
                    font-size: 18pt

                    @media (max-width: 1024px)
                        font-size: 15pt

                    @media (max-width: 640px)
                        font-size: 12pt

            .work-list
                margin-bottom: 60px
                display: flex
                justify-content: center
                flex-wrap: wrap

                figure 
                    flex-basis: 45%
                    height: auto
                    box-sizing: content-box
                    text-align: center
                    cursor: pointer
                    margin: 0 15px

                    @media (max-width: 1024px)
                        flex-basis: 70%
                        margin-bottom: 20px

                    img
                        width: 100%
                        height: auto
                    
                    figcaption 
                        background: #FFF
                        box-sizing: border-box
                        border: 3px solid #E6E9ED
                        border-top-style: none
                        position: relative
                        top: -5px
                        padding: 15px 0
                        
                        @media (max-width: 640px)
                            padding: 5px 0
                            border: 1px solid #E6E9ED
                            font-size: .8em
                        
                        h3,
                        p
                            margin: 0

            .work-carousel
                display: flex
                flex-direction: column
                justify-content: center

                .image-list
                    
                    display: flex
                    justify-content: center

                    img
                        margin: 0 15px

                .carousel-button 
                    height: 30px
                    width: 100%
                    margin-top: 30px
                    text-align: center

                    span 
                        display: inline-block
                        height: 20px
                        width: 20px
                        background: url("../assets/images/product/work-courasel-nav-sprite.png") no-repeat
    
                    .blue-dot 
                        margin: 5px 0
                        background-position: -42px -5px
                        cursor: pointer

                    .green-dot 
                        margin: 5px 0
                        background-position: -67px -5px
                        
                        &:hover 
                            cursor: default	
    
                    .left-nav, 
                    .right-nav 
                        width: 30px
                        height: 30px

                    .right-nav 
                        background-position: -125px 0 
    
</style>
