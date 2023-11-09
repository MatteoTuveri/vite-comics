<template>
    <div>
        <h1>
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

h1{
    margin: 0 auto;
    width: 60%;
    color: white;
}
</style>