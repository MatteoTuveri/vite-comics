<template>
    <ul>
        <li v-for="(item, index) in nav" class="n-hover">
            <div class="flex-grow-1 d-flex align-items-center">
                {{ item }}
            </div>
        </li>
    </ul>
</template>
  
<script>
export default {
    data() {
        return {
            nav: [
                'character',
                'comics',
                'movies',
                'tv',
                'games',
                'collectibles',
                'videos',
                'fans',
                'news',
                'shop'
            ]
        }
    }
}
</script>
  
<style lang="scss" scoped>
li {
    display: flex;
    flex-direction: column;
    text-transform: uppercase;
    list-style: none;
    padding: 0px 10px;
}

li:hover::after {
    content: '';
    width: 100%;
    height: 5px;
    background-color: rgb(3, 128, 245);
}

ul {
    display: flex;
    justify-content: center;
    margin: 0px;
}
</style>