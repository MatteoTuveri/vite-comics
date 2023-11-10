<template>

    <ContentComp />
    <SectionsAreaComp />
    <ReferencesListsComp />

</template>
  
<script>
import ContentComp from './main/ContentComp.vue';
import SectionsAreaComp from './main/SectionsAreaComp.vue';
import ReferencesListsComp from './main/ReferencesListsComp.vue';

export default {
    
    data() {
        return {
            saluti:[
                {
                    ciao:'ciao',
                },
                {
                    ciao:'bella'
                },
                {
                    ciao:'bellissima'
                }
                
        ]

        }
    },
    components:{
    ContentComp,
    SectionsAreaComp,
    ReferencesListsComp
}

}
</script>
  
<style lang="scss" scoped></style>