<template>
    <div class="w-100 bg-img position-relative">
        <div class="position-absolute px-3 py-2 text-uppercase text-white h4">
            Current series
        </div>
    </div>
</template>

<script>

export default{
    data() {
        return {
            
        }
    },
}

</script>

<style lang="scss">
.bg-img{
    background-image: url('/Images/jumbotron.jpg');
    background-size: cover;
    height: 300px;
    div{
        background-color: rgb(2, 130, 249);
        bottom: -10%;
        left: 10%;
    }
}
</style>