<template>
    <section class="slider"
        :style="{ backgroundImage: 'url(' + require(`@/assets/images/carousel/${imgUrl}`) + ')' }">

        <div class="container">
            <div class="content">
                <h1> Hi, I'm a developer</h1>

                <p>
                    Created this online portfolio with the professionally and lovingly designed REEN website template. 
                </p>
                <button>GET STARTED NOW</button>
            </div>
        </div>

    </section>
</template>

<style lang="sass" scoped>
    section.slider
        box-sizing: border-box
        height: 820px
        width: 100%
        margin: 0 auto
        padding: 0
        background-size: cover
        background-repeat: no-repeat
        background-attachment: fixed
        background-position: center center
        max-width: 1920px
        
        @media only screen and (max-width: 1310px)
            height: 600px

        @media only screen and (max-width: 800px)
            height: 400px

        .container
            display: flex
            justify-content: center
            align-items: center
            text-align: center
        
            .content
                
                h1
                    font-size: 50pt
                    font-family: 'tahoma'
                    color: #FFF
                    text-transform: uppercase
                    margin: 0
                    font-weight: bold
                    width: 90%
                    margin: 0 auto
                    
                    @media only screen and (max-width: 1310px)
                        font-size: 3em

                    @media only screen and (max-width: 800px)
                        font-size: 2.5em
                p 
                    font-size: 18pt
                    font-family: "Source Sans Pro"
                    color:#A3B1BF
                    margin: 5px 0
                    width: 80%
                    margin: 0 auto
                    margin-top: 20px

                    @media only screen and (max-width: 1310px)
                        font-size: 16pt
                    
                    @media only screen and (max-width: 800px)
                        font-size: 14pt

                button 
                    color: #FFF
                    height: 50px
                    width: 250px
                    display: flex
                    justify-content: center
                    align-items: center
                    background: #00BC9C
                    border: none
                    margin: 10px auto
                    border-radius: 5px
                    font-size: 10pt
                    font-family: "tahoma"
                    font-weight: bold
                    margin-top: 30px
                    cursor: pointer

                    @media only screen and (max-width: 1310px)
                        height: 40px
                        width: 200px
                        font-size: 8pt
                    
                    @media only screen and (max-width: 800px)
                        height: 40px
                        width: 150px
                        font-size: 8pt

                    &:hover
                        background: #17A78B
</style>

<script>
    export default {
        data: function() {
            return {
                imgUrl: 'carousel-1.png'
            }
        }
    }
</script>

