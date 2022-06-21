<template>
  <div class="row secondFooter py-3">
    <div class="col ms-5 d-flex align-items-center" >
      <button class="my-btn ">SIGN-UP NOW!</button>
    </div>
    <div class="col">
      <div class="d-flex justify-content-center align-items-center">
        <h3>FOLLOW US</h3>
        <img src="../assets/img/footer-facebook.png" alt="" />
        <img src="../assets/img/footer-periscope.png" alt="" />
        <img src="../assets/img/footer-pinterest.png" alt="" />
        <img src="../assets/img/footer-twitter.png" alt="" />
        <img src="../assets/img/footer-youtube.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SocialEndingr",
};
</script>

<style lang="scss">
.secondFooter{
    background-color: #303030;
    h3{
        color: #027eec;
    }
    img{
        padding: 0 1rem;
    }
}
.my-btn{
    border: 2px solid #027eec;
    background-color: #303030;
    padding: .5rem;
    color: white;
}
</style>