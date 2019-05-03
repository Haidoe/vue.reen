<template>
    <section class="offer">
        <h2>Want to work with us?</h2>
        <p>
            Magnis modipsae que voloratati andigen daepeditem quiate re porem aut labor. Laceaque quiae sitiorem rest non restibusaes maio es dem tumquam.
        </p>
        <button> GET IN TOUCH </button>
    </section>
</template>

<style lang="sass" scoped>

    .offer 
        background: #FFF
        height: auto
        text-align: center
        justify-content: center
        box-sizing: border-box
        padding: 80px 0
        
        @media (max-width: 640px)
            padding: 50px 15px
        h2 
            font-weight: normal
            font-family: "Tahoma"
            color: #506A85
            font-size: 30pt
            margin-top: 0

            @media (max-width: 640px)
                font-size: 24pt

        p 
            color: #73879C
            font-size: 15pt
            width: 700px
            margin: 10px auto
            margin-bottom: 30px
            
            @media (max-width: 1024px)
                width: 80%
            
            @media (max-width: 640px)
                width: 90%
                font-size: 12pt

        button 
            height: 50px
            width: 160px
            background: #00BC9C
            color: #FFF
            border-style: none
            border-radius: 10px
            font-weight: bold
            cursor: pointer

            &:hover
                background: #17A78B
            
            @media (max-width: 640px)
                width: 120px

</style>
