<template>
    <div class="container">
        <LogoComp />
        <NavComp />
    </div>
</template>
  
<script>
import LogoComp from './header/LogoComp.vue';
import NavComp from './header/NavComp.vue';

export default {
    data() {
        return {};
    },
    components: { LogoComp, NavComp }
}
</script>
  
<style lang="scss" scoped>
.container {
    display: flex;
    justify-content: space-between;
    padding: 0px 20px;
    width: 60%;
    margin: 0 auto;
}
</style>