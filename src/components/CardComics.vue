<template>
    
        <div class="img-card container-card">

            <img :src="fumetti.thumb" alt="image">
            <h4>{{fumetti.series}}</h4>

        </div>
    
</template>

<script>

    export default {

        name: 'CardComicsBlack',

        props:{

            fumetti: Object,
        }
    }

</script>

<style lang="scss" scoped>

.img-card{

    color: white;
    text-align: center;

}

.container-card{
    width: calc(100% / 6);
    padding: 10px 0;
}

</style>