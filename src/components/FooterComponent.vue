<template>
    <div class="bg-footer d-flex align-items-center">
        <div class="container d-flex justify-content-between align-items-center">
            <CallToAction />
            <FollowUsComp />
        </div>
    </div>
</template>
  
<script>
import CallToAction from './footer/CallToAction.vue';
import FollowUsComp from './footer/FollowUsComp.vue';

export default {
    data() {
        return {};
    },
    components: { CallToAction, FollowUsComp }
}
</script>
  
<style lang="scss" scoped>
.bg-footer {
    background-color: rgb(48, 48, 48);
    width: 100%;
    height: 150px;
}
</style>