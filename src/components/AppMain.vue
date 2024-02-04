<script>
export default {
    props: {
        comics: Array
    }
}
</script>
<template>
    <main>
        <div class="container card-container">
            <div class="comics-container" v-for="(comic, i) in comics" :key="i">
                <img :src="comic.thumb" alt="">
                <h4>{{ comic.series }}</h4>
            </div>
        </div>
    </main>
</template>
<style lang="scss" scoped>
main {
    background-color: black;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;

    .card-container {
        margin: 10px 0;
        display: flex;
        flex-wrap: wrap;

        .comics-container {
            flex-basis: calc(100% / 6);
            padding: 10px;

            img {
                width: 150px;
            }
        }
    }
}
</style>