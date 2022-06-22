<template>
    <div class="my-Jumbo">
        <img src="../assets/img/jumbotron.jpg" alt="">
    </div>
</template>
<script>
export default {
    props:{
        jumboImg:String
    }
}
</script>
<style lang="scss">
    .my-Jumbo{
        height: 500px;
        overflow: hidden;
       img{
        width: 100%;
        object-fit: cover;
        object-position: center;
       }
    }
</style>