<script>
export default {
    data: () => ({
        links: [
            {
                text: 'Characters',
                url: '#',
                current: false,
            },
            {
                text: 'Comics',
                url: '#',
                current: true,
            },
            {
                text: 'Movies',
                url: '#',
                current: false,
            },
            {
                text: 'TV',
                url: '#',
                current: false,
            },
            {
                text: 'Games',
                url: '#',
                current: false,
            },
            {
                text: 'Collectibles',
                url: '#',
                current: false,
            },
            {
                text: 'Videos',
                url: '#',
                current: false,
            },
            {
                text: 'Fans',
                url: '#',
                current: false,
            },
            {
                text: 'News',
                url: '#',
                current: false,
            },
            {
                text: 'Shop',
                url: '#',
                current: false,
            }
        ]
    })
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

<style scoped>
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 12px 0;
}

img {
    width: 80px;
}

header ul {
    width: 70%;
    display: flex;
    justify-content: space-between;
    font-size: 1rem;
    list-style-type: none;
}

ul li {
    font-weight: bold;
}
</style>