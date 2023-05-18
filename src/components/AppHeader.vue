<script>

export default {

}
</script>

<template>
    <header>
        <div>img</div>
        <ul>
            <li><a href="#">CHARACTERS</a></li>
            <li><a href="#">COMICS</a></li>
            <li><a href="#">MOVIES</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">GAMES</a></li>
            <li><a href="#">COLLECTIBLES</a></li>
            <li><a href="#">VIDEOS</a></li>
            <li><a href="#">FANS</a></li>
            <li><a href="#">NEWS</a></li>
            <li><a href="#">SHOP</a></li>
        </ul>
    </header>
</template>

<style lang="scss" scoped>
header {
    display: flex;
    align-items: center;
    justify-content: space-around;
    background-color: #FFF;
    height: 5rem;
}
ul {
    display: flex;
    li{
        list-style: none;
        padding-inline: .6rem;
        a {
            text-decoration: none;
            color: black;
        }
    }
}
</style>