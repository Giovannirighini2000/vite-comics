<template>
    <li class="basis-img">
        <img :src="thumb" alt="">
        <h4>
            {{ series }}
        </h4>

    </li>
</template>
<script>
export default {
    props: {
        thumb: String,
        series: String,



    }
}
</script>
<style lang="scss">
.basis-img {
    flex-basis: 15%;
}
</style>