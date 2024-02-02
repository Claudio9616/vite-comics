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
<template>
    <footer>
        <div class="row">
            <!-- fare 4 ul più img -->
        </div>
    </footer>
</template>
<style scoped>
footer {
    height: 300px;
    display: flex;
    justify-content: space-between;
    background-image: url(../assets/img/footer-bg.jpg);
}

.row {
    display: flex;
    border: 1px solid white;
    flex-wrap: wrap;
    align-items: center;
    width: 266px;
}

ul {
    list-style-type: none;
    color: white;
    margin: 30px;
}
</style>   