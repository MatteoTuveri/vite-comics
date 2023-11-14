<template>
    <div class="bg-contain">
        <JumboTron />
        <div class="container">
            <div class="row p-5">
                <GalleryCards v-for="(item,index) in comicsList" :img="item.img" :name="item.name" />
            </div>
        </div>
    </div>
</template>
  
<script>
import JumboTron from './Content/JumboTron.vue';
import GalleryCards from './Content/GalleryCards.vue';
import axios from 'axios';


export default {
    data() {
        return {
            comicsList: [],
        };
    },
    methods: {
        getData() {
            axios.get('/dc-comics.json').then((response) => {
                const data = response.data;
                for (let i = 0; i < data.length; i++) {
                    this.comicsList.push({
                        name: data[i].series,
                        img: data[i].thumb
                    })
                }
                console.log(this.comicsList);
            })
        }
    },
    mounted() {
        this.getData();
    },
    components: { JumboTron, GalleryCards }
}
</script>
  
<style lang="scss" scoped>
.bg-contain {
    background-color: rgb(28, 28, 28);
}
</style>