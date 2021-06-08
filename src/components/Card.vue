<template>
    <div class="item">
        <img :src="comics.thumb" alt="">
        <p>{{ comics.series }}</p>
    </div>
</template>

<script>
export default {
    name: 'Card',
    props: ["comics"]
}
</script>

<style lang="scss" scoped>
    .item {
        width: calc(100% / 6 - 2%);
        margin: 1%;
        img {
            width: 150px;
            height: 200px;
            object-fit: initial;
            object-position: center;
        }
        p {
            font-size: 13px;
            text-transform: uppercase;
            color: white;
        }
    }
    
</style>