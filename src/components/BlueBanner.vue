<template>
    <div class="ps-4 myBlueBanner py-5">
       <div class="row text-center">
        <div class="col" v-for="link in blueBannerLinks" :key="link.title">
        
        {{link.title}}
        </div>
       </div>
    </div>
</template>


<script>
export default {
    name:"TheContent",
    data() {
        return {
            blueBannerLinks:[
                {
                    title:"DIGITAL COMICS",
                    img:"/assets/img/buy-comics-digital-comics.pmg"
                },
                {
                    title:"DC MERCHANDISE",
                    img:"percorsoImmagine"
                },
                {
                    title:"SUBSCRIPTION",
                    img:"percorsoImmagine"
                },
                {
                    title:"COMIC SHOP OCATOR",
                    img:"percorsoImmagine"
                },
                {
                    title:"DC POWER VISA",
                    img:"percorsoImmagine"
                }
            ]
        }
    },
}
</script>

<style lang="scss">
    .myBlueBanner{
        background-color: #0282f9;
        color:white
    }
</style>