<template>
  <div>
    
      
        <div class="mycard">
        <div class="card-image-squared">
          <img :src="cardImg" alt="" />
        </div>
        <div class="title-of-img py-3">
          <h6>{{ cardTitle }}</h6>
        </div>
      </div>
      </div>
    
</template>

<script>
export default {
  props: {
    cardTitle: String,
    cardImg: String,
  },
};
</script>

<style lang="scss">
.mycard {
    text-align: left;
}

</style>