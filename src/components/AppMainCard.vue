<template>
    <li class="basis-img">
        <img class="height-img" :src="thumb" alt="">
        <h4 class="white">
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

.height-img {
    height: 225px;
    width: 200px;
}
</style>