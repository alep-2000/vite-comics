<script>
import ComicsBooks from '../data/comicsBooks.js'
import CardVue from './card.vue'

export default {
    components: {
        CardVue
    },
    data() {
        return {
            comicsBooks: ComicsBooks
        }
    }
}
</script>

<template lang="">
    <div>
        <div class="background">
            <div class="sub-container">
                <div class="flex">
                    <CardVue v-for="(comicBook, index) in comicsBooks" :key="index"  :img="comicBook.thumb" :series="comicBook.series"/>
                        
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

.background {
    background-color: black;

    .sub-container {
        width: 60%;
        margin: 0 auto;

        .flex {
            display: flex;
            flex-wrap: wrap;

            .card {
                width: calc(100% / 6);
                color: white;
            }
        }
    }
}
</style>