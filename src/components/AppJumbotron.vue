<script>

export default{
  data(){
    return{

    }
  },
}

</script>

<template>
    <div class="jumbotron d-flex">
         <div class="current-series justify-content-center"><p><b>CURRENT SERIES</b></p></div>
    </div>
</template>

<style lang="scss" scoped>
    .jumbotron{
        background-image: url("../assets/img/jumbotron.jpg");
        height: 400px;
        position: relative;
        .current-series{
            position: absolute;
            bottom: -21px;
            left: 450px;
            background-color: #5774F3;
            padding: 10px 50px;
            color: white;
        }
    }
</style>    
