<template>
    <div class="wrapper ">
        <JumboComponent />
        <div class="bg-dark">
            <div class="container  h-100 text-white">
                <div class="row mx-auto">
                    <CardComponent :image="card.thumb" :title="card.series" v-for="card in cards"/>
                </div>
                <button class="text-uppercase mx-auto d-block btn btn-primary rounded-0">Load More</button>
            </div>
        </div>
    </div>
</template>

<script>
    import {cards} from '../data/data';
    import CardComponent from './CardComponent.vue';
    import JumboComponent from './JumboComponent.vue';
    export default {
        name: 'MainComponent',
        components: {
            JumboComponent,
            CardComponent
        },
        data(){
            return{
                cards: [...cards]
            }
        }
    }
</script>

<style lang="scss" scoped>
    .wrapper{
        height: calc(100vh - (20vh + 90px + 55px + 90px));
    }
    button.fs-5{
        position: absolute;
        bottom: -5%;
        left: 3%;
        z-index: 100;
    }
    .bg-dark{
        padding-top: 3rem;
        height: calc(100% - 20vh);
        overflow-y: auto;
    }
</style>