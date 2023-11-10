<template>
    <div >
        <h1 class="container text-white">
            {{ title }}
        </h1>
    </div>
</template>
  
<script>
export default {
    data() {
        return {
            title:'--> Content Goes Here <--'
        }
    }
}
</script>
  
<style lang="scss" scoped>
div{
    background-color: rgb(28, 28, 28);
    padding: 40px 0;
}
</style>