<template>
    <ul>
        <li v-for="(item, index) in nav">
            <div>
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
    vertical-align: center;
    text-transform: uppercase;
    list-style: none;
    padding: 0px 10px;
    display: flex;
    align-items: center;
}

ul {
    display: flex;
    justify-content: center;
    margin: 0px;
}
</style>