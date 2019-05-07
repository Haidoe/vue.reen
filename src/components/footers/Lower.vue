<template>
    <footer class="lower">
        <div class="container">

            <p> © 2019 HAIDOE. All rights reserved. </p>
            
            <ul>
                <li> Home </li>
                <li> About </li>
                <li> Projects </li>
                <li> Contact </li>
            </ul>
            
        </div>
    
    </footer>
</template>

<style lang="sass" scoped>
    .lower 
        background: #283645
        height: 80px
        color: #707E8C
        
        @media (max-width:1024px)
            height: auto
            padding: 10px
    
        .container
            display: flex
            justify-content: space-between
            align-items: center
            padding: 0 15px
            
            @media (max-width: 700px)
                justify-content: center

            p
                @media (max-width: 1150px)
                    font-size: .9em
                    
            ul
                @media (max-width: 700px)
                    display: none
            li 
                display: inline
                font-weight: bold
                margin: 0 10px
                cursor: pointer
                &:hover
                    color: #00BC9C

                @media (max-width: 1150px)
                    font-size: .9em
                    margin: 0 5px

            li + li::before 
                content: "·"
                padding-right: 15px
                color: #707E8C

                @media (max-width: 1150px)
                    padding-right: 15px

            li + li:hover::before 
                cursor: default
</style>

