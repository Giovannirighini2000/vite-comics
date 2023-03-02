<template>
    <div class="container-img-jumbo">
        <img class="jumbo" src="/img/jumbotron.jpg" alt="">

    </div>
</template>
<script>
export default {

}
</script>
<style lang="scss">
.container-img-jumbo {
    height: 450px;
    overflow: hidden;
}

.jumbo {
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center top;
}
</style>