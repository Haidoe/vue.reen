<template>
    <section class="services">
        <div class="container">
            
            <div class="upper-content">
                <h1>
                    Beautiful. Clean. Responsive.
                </h1>
                <p>
                    REEN is a high-quality solution for those who want a beautiful website in no time. It's fully responsive and will adapt itself to any mobile device. iPad, iPhone, Android, it doesn't matter. Your content will always looks its absolute best.
                </p>
            </div>

            <div class="lower-content">
                
                <div class="lower-content-list">
                    <div class="logo" id="passion"></div>
                    <div class="content">
                        <h3> Passion </h3>
                        <p> Magnis modipsae que lib voloratati andigen daepeditem quiate re porem aut labor. Laceaque quiae sitiorem rest non restibusaes maio es dem tumquam core posae volor remped modis volor. </p>
                    </div>
                </div>
                
                <div class="lower-content-list">
                    <div class="logo" id="creativity"></div>
                    <div class="content">
                        <h3> Creativity </h3>
                        <p>Magnis modipsae que lib voloratati andigen daepeditem quiate re porem aut labor. Laceaque quiae sitiorem rest non restibusaes maio es dem tumquam core posae volor remped modis volor.</p>
                    </div>
                </div>

                <div class="lower-content-list">
                    <div class="logo" id="quality"></div>
                    <div class="content">
                        <h3> Quality </h3>
                        <p> Magnis modipsae que lib voloratati andigen daepeditem quiate re porem aut labor. Laceaque quiae sitiorem rest non restibusaes maio es dem tumquam core posae volor remped modis volor.</p>
                    </div>
                </div>
            </div>

        </div>
    </section>
</template>

<style lang="sass" scoped>
    .services 
        background: #FFF
        height: 675px
        
        @media (max-width: 1310px)
            min-height: 675px
            height: auto
            padding: 50px 0

        .container
            display: flex
            flex-direction: column
            justify-content: center
            
            @media (max-width: 1310px)
                padding: 0 20px

            .upper-content
                text-align: center
                width: 70%
                margin: 0 auto

                @media (max-width: 800px)
                        width: 90%
                
                h1
                    font-size: 35pt
                    font-weight: normal
                    margin: 0

                    @media (max-width: 800px)
                        font-size: 2.3em
                p
                    font-size: 17pt
                    color: #73879C

                    @media (max-width: 800px)
                        font-size: 1.2em
    

            .lower-content 
                text-align: left
                display: flex
                flex-wrap: wrap
                justify-content: space-around
                margin-top: 50px
                
                @media (max-width: 1310px)
                    justify-content: flex-start
                @media (max-width: 1024px)
                    justify-content: center

                .lower-content-list
                    flex-basis: 30%
                    display: flex
                    justify-content: space-between
                    
                    @media (max-width: 1310px)
                        flex-basis: 45%
                    @media (max-width: 1024px)
                        flex-basis: 90%
                    .logo 
                        width: 70px
                        height: 80px
                        background: url("../assets/images/services-logo-sprites.png") no-repeat

                    .content
                        flex-basis: 75%
                                            
                    #passion 
                        background-position: 2px 10px

                    #creativity 
                        background-position: -87px 10px

                    #quality 
                        background-position: -182px 10px

</style>
