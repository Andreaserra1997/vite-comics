<script></script>

<template>
<main>
<div class="content-top">
    <div>--Content goes here--</div>
</div>
<div class="content-down">
        <ul>
            <li>
                <img src="../../img/buy-comics-digital-comics.png" alt=""><a href="#">DIGITAL COMICS</a>
            </li>
            <li>
                <img src="../../img/buy-comics-merchandise.png" alt=""><a href="#">DC MERCHANDISE</a>
            </li>
            <li>
                <img src="../../img/buy-comics-subscriptions.png" alt=""><a href="#">SUBSCRIPTION</a>
            </li>
            <li>
                <img class="location" src="../../img/buy-comics-shop-locator.png" alt=""><a href="#">COMIC SHOP LOCATOR</a>
            </li>
            <li>
                <img src="../../img/buy-dc-power-visa.svg" alt=""><a href="#">DC POWER VISA</a>
            </li>
        </ul>
</div>
</main>
</template>

<style lang="scss" scoped>
.content-top {
    height: 100px;
    background-color: #1C1C1C;
    color: white;
}
.content-down {
    background-color: #0282F9;
}
ul {
    display: flex;
    justify-content: center;
    max-width: 1000px;
    margin: auto;
    li {
        display: flex;
        align-items: center;
        list-style: none;
        height: 5rem;
        padding-inline: 3rem;
        img {
            width: 50%;
            padding-right: .5rem;
        }
        .location {
            width: 30%;
        }
        a {
            text-decoration: none;
            font-size: .8rem;
            white-space: nowrap;
            color: #FFF;
        }
    }
}
</style>