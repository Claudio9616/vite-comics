<script>
export default {
    props: {
        links: Array
    }
}
</script>
<!-- ricordati di fissare il link.url in un tag a -->
<template>
    <header class="container">
        <img src="../assets/img/dc-logo.png" alt="">
        <ul>
            <li v-for="(link, i) in links" :key="i">
                {{ link.text }}
            </li>
        </ul>
    </header>
</template>

<style lang="scss" scoped>
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 12px 0;

    img {
        width: 80px;
    }

    ul {
        width: 70%;
        display: flex;
        justify-content: space-between;
        font-size: 1rem;
        list-style-type: none;

        li {
            font-weight: bold;
        }
    }

}
</style>