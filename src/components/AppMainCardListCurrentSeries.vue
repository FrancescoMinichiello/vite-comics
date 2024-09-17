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
            <div>
                <img :src="cardThumbs" class="card-thumb" alt="">
            </div>
</template>

<style lang="scss" scoped>
    .card-thumb{
        height: 150px;
        width: 150px;
    }

</style>    
