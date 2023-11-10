<template>
    <div class="container d-flex justify-content-between">
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
</style>