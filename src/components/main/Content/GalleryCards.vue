<template>
    <div class="col-lg-2 col-md-4 col-12 p-2 d-flex flex-column align-items-center">
        <div class="img">
            <img :src="img" :alt="name">
        </div>
        <div class="text-center text-white text-uppercase py-2">
            {{ name }}
        </div>
    </div>
</template>

<script>

export default{
    name:'GalleryCards',
    data() {
        return {
            
        }
    },
    props:{
        img: String,
        name: String
    }
}

</script>

<style lang="scss" scoped>
img{
    width: 150px;
    height: 150px;
    object-fit: cover;
    object-position: top;
}
</style>