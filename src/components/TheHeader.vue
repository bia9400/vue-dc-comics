<template>
  <div>
    <div class="row py-3">
      <div class="col d-flex justify-content-center">
        <div class="logo">
          <img src="../assets/img/dc-logo.png" alt="" />
        </div>
      </div>
      <div class="col-7 d-flex  " >
        <ul class="d-flex list-unstyled">
          <li class="text-uppercase px-3 align-self-center" v-for="link in linkList" :key="link"><a href="#">{{link}}</a></li>
        </ul>
      </div>
    </div>
  </div>
</template>


<script>
export default {
    name:"TheHeader",
    data() {
        return {
            linkList:[
                "characters",
                "comics",
                "movies",
                "tv",
                "games",
                "collectible",
                "videos",
                "fans",
                "news",
                "shop"
            ]
        }
    },
    
    }

    

</script>


<style lang="scss">
li{
    list-style: none;

    a{
        color:black;
        text-decoration: none;
        font-weight: bold;
        font-size: 1rem;

        
    }
    & a:hover {
            border-bottom: 2px solid #0282f9;
        }
}

</style>