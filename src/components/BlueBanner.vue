<template>
    <div class="ps-4 myBlueBanner py-5">
       <div class="container">
        <div class="row text-center">
        <div class="col" v-for="link in blueBannerLinks" :key="link.title">
        <img :src="`img`+link.img" alt="" style="aspect-ratio: 1; width: 50px;">
        {{link.title}}
        </div>
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
                    img:"/buy-comics-digital-comics.png"
                },
                {
                    title:"DC MERCHANDISE",
                    img:"/buy-comics-merchandise.png"
                },
                {
                    title:"SUBSCRIPTION",
                    img:"/buy-comics-subscriptions.png"
                },
                {
                    title:"COMIC SHOP LOCATOR",
                    img:"/buy-comics-shop-locator.png"
                },
                {
                    title:"DC POWER VISA",
                    img:"/buy-dc-power-visa.svg"
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