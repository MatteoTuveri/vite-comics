<template>
    <div class="bg">
        <ul>
            <li v-for="(item,index) in icons">
                <div class="img">
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
            icons:[
                {
                    image:'/Images/buy-comics-digital-comics.png',
                    title:'digital comics'
                },
                {
                    image:'/Images/buy-comics-merchandise.png',
                    title:'dc merchandise'
                },
                {
                    image:'/Images/buy-comics-subscriptions.png',
                    title:'subscription'
                },
                {
                    image:'/Images/buy-comics-shop-locator.png',
                    title:'comic shop locator'
                },
                {
                    image:'/Images/buy-dc-power-visa.svg',
                    title:'dc power visa'
                },
            ]
        }
    }
}
</script>
<style lang="scss" scoped>
ul{
    list-style: none;
    display: flex;
    justify-content: space-between;
    width: 60%;
    margin: 0 auto;
}
li{
    display: flex;
    align-items: center;
}

img{
    width: 100%;
    padding: 0 10px;
}

.img{
    width: 80px;
}
.title{
    text-transform: uppercase;
    color: white;
}

.bg{
    background-color: rgb(2, 130, 249);
    padding: 40px;
}
</style>