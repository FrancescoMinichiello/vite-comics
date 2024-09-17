<script>
export default{
  data(){
    return{
        items: [
      { 
        img: 'buy-comics-digital-comics.png',
        name: 'DIGITAL COMICS' 
      },
      { 
        img: 'buy-comics-merchandise.png',
        name: 'DC MERCHANDISE' 
      },
      { 
        img: 'buy-comics-subscriptions.png',
        name: 'SUBSCRIPTION'
      },
      { 
        img: 'buy-comics-shop-locator.png',
        name: 'COMIC SHOP LOCATOR'
      },
      {
         img: 'buy-dc-power-visa.svg',
         name: 'DC POWER VISA' 
      }
    ]
    }
  },
  methods:{
    getImage(imagePath){
      return new URL(`../assets/img/${imagePath}`, import.meta.url).href;
    }
  }
}
</script>

<template>
<div class="container-fluid d-flex justify-content-center">
    <div class="row py-5">
        <div class="item" v-for="item in items">
          <img :src="getImage(item.img)" :alt="item.name"> {{ item.name }}
        </div>
    </div>
</div>
</template>

<style lang="scss" scoped>
@use 'bootstrap/scss/bootstrap.scss' as *;
.container-fluid{
    background-color: #5774F3;
    width: 100%;
    .item {
      width: calc(100% / 5);
      text-align: center;
      min-width: 300px;
      color: white;
    }
    img{
      height: 50px;
      width: 50px;
      object-fit: contain;
      margin-right: 10px;
    }
}
</style>    
