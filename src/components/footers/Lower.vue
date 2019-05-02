<template>
    <footer class="lower">
        <div class="lower-footer-container">
            <div class="left">
                © 2014 REEN. All rights reserved.
            </div>
            <div class="right">
                <ul>
                    <li> Home </li>
                    <li> Portfolio </li>
                    <li> Blog </li>
                    <li> About </li>
                    <li> Services </li>
                    <li> Contact </li>
                </ul>
            </div>
            <div class="btn-up"></div>
        </div>
    </footer>
</template>

<style scoped>
    footer.lower {
        background: #283645;
        height: 80px;
        color: #707E8C;
        font-family: "Source Sans Pro"
    }

    .lower-footer-container {
        width: 70%;
        height: inherit;
        margin: 0 auto;
        padding: 0 15px;
        box-sizing: border-box;
        max-width: 1366px;
    }
    .lower-footer-container div.left {
        margin: 30px 0;
    }

    .lower-footer-container div.right ul {
        margin: 30px 0;
    }

    .lower-footer-container div.right ul li {
        display: inline;
        font-weight: bold;
        margin: 0 10px;
    }

    .lower-footer-container div.right ul li:hover {
        cursor: pointer;
        color: #00BC9C;
    }

    .lower-footer-container div.right ul li + li::before {
        content: "·";
        padding-right: 15px;
        color: #707E8C;
    }

    .lower-footer-container div.right ul li + li:hover::before {
        text-decoration: none !important;
        cursor: default;
    }

    footer.lower .left {
        float: left
    }

    footer.lower .right {
        float: right;
    }

    footer.lower .btn-up {
        position: absolute;
        margin-top: 20px;
        right: 30px;
        height: 40px;
        width: 40px;
        background: url("../../assets/images/footer/btn-up.png");
        cursor: pointer;
    }
</style>

