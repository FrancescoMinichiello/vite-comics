<script>
export default{
  data(){
    return{

    }
  },
  props:{
    cardThumbs : {
    type: String,
    required: true,
    },
    cardSeries:{
        type:String,
        required: true,
    }
  },
}
</script>

<template>
            <div class="box-card" >
                <img :src="cardThumbs" class="card-thumb" :alt="cardSeries">
                <p>{{ cardSeries }}</p>
            </div>
</template>

<style lang="scss" scoped>
    .box-card{
        min-height: 200px;
        width: 150px;
        color: white;
    }
    .card-thumb{
        height: 150px;
        width: 100%;
    }
</style>    
