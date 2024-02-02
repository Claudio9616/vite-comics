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
        <div class="row container">
            <div class="content-footer-top">
                <ul>
                    <li>DC COMICS</li>
                    <li v-for="(link, i) in links">
                        <a :href="link.url">{{ link.text }}</a>
                    </li>
                </ul>
                <ul>
                    <li>DC</li>
                    <li v-for="(link, i) in links">
                        <a :href="link.url">{{ link.text }}</a>
                    </li>
                </ul>
                <ul>
                    <LI>SITES</LI>
                    <li v-for="(link, i) in links">
                        <a :href="link.url">{{ link.text }}</a>
                    </li>
                </ul>
                <ul>
                    <li>SHOP</li>
                    <li>
                        <a href="#">Shop DC</a>
                    </li>
                    <li>
                        <a href="#">Shop DC Collectibles</a>
                    </li>
                </ul>
            </div>
            <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>
        <div class="footer-bot">
            <div class="container content">
                <button>SIGN-UP-DOWN</button>
                <div class="icons">
                    <ul>
                        <li>FOLLOW US</li>
                        <li>
                            <img src="../assets/img/footer-facebook.png" alt="">
                        </li>
                        <li>
                            <img src="../assets/img/footer-twitter.png" alt="">
                        </li>
                        <li>
                            <img src="../assets/img/footer-youtube.png" alt="">
                        </li>
                        <li>
                            <img src="../assets/img/footer-pinterest.png" alt="">
                        </li>
                        <li>
                            <img src="../assets/img/footer-periscope.png" alt="">
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<style scoped>
footer {
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: contain;
}

.row {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 80px;
    padding: 20px 0;
    height: 425px;
}

.content-footer-top {
    display: flex;
    flex-wrap: wrap;
    width: 400px;
    gap: 30px
}

ul {
    list-style-type: none;
    color: white;
    margin: 10px;
}

ul li:first-child {
    color: white;
    font-size: 1.2rem;
    font-weight: bold;
    margin-bottom: 10px;
}

a {
    text-decoration: none;
    color: #959595;
}

.row img {
    width: 425px;
}

.footer-bot {
    height: 100px;
    background-color: #303030;
    position: absolute;
    right: 0;
    left: 0;
}

.content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 100%;
}

button {
    height: 50px;
    background-color: #303030;
    color: white;
    border: 2px solid #0282F9;
    padding: 15px;
}

.icons ul {
    display: flex;
    align-items: center;
    justify-content: center;
}

.icons ul li {
    margin: 0 10px;
}

.icons ul li:first-child {
    color: #0282F9;
}

img {
    width: 30px;
}
</style>   