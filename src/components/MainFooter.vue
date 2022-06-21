<template>
  <div class="logoContainer px-5">
    <div class="row ">
      <div class="col">
        <div class="row mt-3">
          <div v-for="(array,i) in footerArray" class="col-4" :key="i">
          <h3>{{array.title}}</h3>
          <ul class="list-unstyled">
            <li v-for="content in footerArray[i].valueArray" :key="content">{{content}}</li>
          </ul>
          </div>
          
        </div>
      </div>
      <div class="col strange-image">
        <img src="../assets/img/dc-logo-bg.png" alt="">
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "MainFooter",
  data() {
    return {
      footerArray: [
        {
          title: "DC COMICS",
          valueArray: [
            "characters",
            "comics",
            "movies",
            "tv",
            "games",
            "collectible",
            "videos",
            
          ],
        },
        {
          title: "DC",
          valueArray: [
            "Terms of Use",
            "Privacy Policies",
            "movies",
            "tv",
            "games",
            "collectible",
            "Privacy Policies",
            "videos",
            "fans",
            "news",
            "shop",
          ],
        },
        {
          title: "SITES",
          valueArray: [
            "MAD MAGAZINE",
            "DC",
            "DC KIDS",
            "DC UNIVERS",
            "DC POWER VISA",
            
            
          ],
        },
        {
          title: "SHOP",
          valueArray: [
            "SHOP DC COLLECTIBLES",
            "SHOP DC",
            
            
            
          ],
        },
      ],
    };
  },
};
</script>

<style lang="scss">
.logoContainer {
    color: white;
  background-image: url("../assets/img/footer-bg.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  li{
    color: #959595;
  }
  .strange-image{
    overflow: hidden;
    align-items: center;
    display: flex;
    justify-content: center;
    img{
        height: 150%;
        
    }
  }
}
</style>