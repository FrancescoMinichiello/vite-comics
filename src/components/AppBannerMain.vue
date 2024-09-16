<script>
export default{
  data(){
    return{
        items: [
      { 
        img: '',
        name: 'DIGITAL COMICS' 
      },
      { 
        img: '',
        name: 'DC MERCHANDISE' 
      },
      { 
        img: '',
        name: 'SUBSCRIPTION'
      },
      { 
        img: '',
        name: 'COMIC SHOP LOCATOR'
      },
      {
         img: '',
         name: 'DC POWER VISA' 
      }
    ]
    }
  }
}
</script>

<template>
<div class="container-fluid d-flex justify-content-center">
    <div class="row py-5">
        <div class="item" v-for="item in items">
            {{ item.name }}
        </div>
    </div>
</div>
</template>

<style lang="scss" scoped>
@use 'bootstrap/scss/bootstrap.scss' as *;
.container-fluid{
    background-color: #5774F3;
    width: 100%;
}
.item {
  width: calc(100% / 5);
  text-align: center;
  min-width: 300px;
  color: white;
}
</style>    
