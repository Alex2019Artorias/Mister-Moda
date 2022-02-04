<template>
    <div class="container">
        <!-- <Carousel :dots="false" :nav="false" :autoplayHoverPause="true" :autoplay="true" :autoplaySpeed="1"> 
            <img src="https://placeimg.com/200/200/any?1">
            <img src="https://placeimg.com/200/200/any?2">
            <img src="https://placeimg.com/200/200/any?3">
            <img src="https://placeimg.com/200/200/any?4">
            <img src="https://placeimg.com/200/200/any?1">
            <img src="https://placeimg.com/200/200/any?2">
            <img src="https://placeimg.com/200/200/any?3">
            <img src="https://placeimg.com/200/200/any?4">
        </Carousel> -->
    </div>
</template>

<script>
// import Carousel from 'vue-owl-carousel'


export default {
    components: {
        // Carousel
    },
}
</script>

<style lang='scss' scoped>
@use './../scss/colors';
@use './../scss/mixins';

.con {
    height: 1000px;
    width: 1000px;
    background-color: colors.$red;
}

.item {
    background-color: black;
    border: 1px solid rgb(29, 159, 199);
    width: 100px;
    height: 100px;
}

@include mixins.mobile-only {
    .con {
        background-color: #000000;
    }
}
</style>