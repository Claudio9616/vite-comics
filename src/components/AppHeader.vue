<script>
export default {
    name: 'APPHEADER',
}
</script>

<template>
    <header class="container">
        <img src="../assets/img/dc-logo.png" alt="">
        <ul>
            <li>CHARACTERS</li>
            <li>COMICS</li>
            <li>MOVIE</li>
            <li>TV</li>
            <li>GAMES</li>
            <li>COLLECTIBLES</li>
            <li>VIDEOS</li>
            <li>FAN</li>
            <li>NEWS</li>
            <li>SHOP</li>
        </ul>
    </header>
    <h1>guerhbvubu</h1>
</template>

<style scoped>
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    border: 1px solid blue;
}

header ul {
    width: 70%;
    display: flex;
    justify-content: space-between;
    font-size: 1rem;
    list-style-type: none;
    border: 1px solid red;
}

ul li {
    height: 100%;
}
</style>