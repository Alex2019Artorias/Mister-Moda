<template>
    <div class="con">
        <div class="item"></div>
        <div class="item"></div>
        <div class="item"></div>
        <div class="item"></div>
        <div class="item"></div>
        <div class="item"></div>
        <div class="item"></div>
        <div class="item"></div>
    </div>
</template>

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