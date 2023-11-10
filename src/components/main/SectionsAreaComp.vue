<template>
    <div class="bg">
        <ul class="container d-flex justify-content-between">
            <li v-for="(item, index) in icons">
                <div class="img">
                    <div v-if="locator"></div>
                    <img :src="item.image" :alt="item.title">
                </div>
                <div class="title">
                    {{ item.title }}
                </div>
            </li>
        </ul>

    </div>
</template>
  
<script>
export default {
    data() {
        return {
            icons: [
                {
                    image: '/Images/buy-comics-digital-comics.png',
                    title: 'digital comics'
                },
                {
                    image: '/Images/buy-comics-merchandise.png',
                    title: 'dc merchandise'
                },
                {
                    image: '/Images/buy-comics-subscriptions.png',
                    title: 'subscription'
                },
                {
                    image: '/Images/buy-comics-shop-locator.png',
                    title: 'comic shop locator'
                },
                {
                    image: '/Images/buy-dc-power-visa.svg',
                    title: 'dc power visa'
                },
            ],
            locator:false,
        }
    }
}
</script>
<style lang="scss" scoped>
ul {
    list-style: none;
}

li {
    display: flex;
    align-items: center;
}

img {
    width: 100%;
    padding: 0 10px;
}

.img {
    width: 80px;

}

.title {
    text-transform: uppercase;
    color: white;
}

.bg {
    background-color: rgb(2, 130, 249);
    padding: 40px;
}
</style>