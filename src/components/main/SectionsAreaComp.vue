<template>
    <div class="bg">
        <ul class="container d-flex justify-content-between">
            <li v-for="(item, index) in icons">
                <div class="img">
                    <div v-if="item === icons[4]" class="gap-loc"></div>
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
    float: left;
    width:  50px;
    height: 50px;
    object-fit: contain;
}

.gap-loc{
    width: 100%;
    height: 20px;
}

.img {
    padding: 10px;
    display: flex;
    align-items: center;
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