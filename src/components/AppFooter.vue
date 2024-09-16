<script>
export default{
  data(){
    return{

    }
  }
}
</script>

<template>
  <footer>
    <div class="container-fluid">
      <div class="row row-cols-2">
        <div class="col footer-links">

        </div>
        <div class="col footer-image">
        </div>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
@use 'bootstrap/scss/bootstrap.scss' as *;
footer{
  min-height: 500px;
  background-image: url("../assets/img/footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  .footer-image{
    background-image: url("../assets/img/dc-logo-bg.png");
    background-repeat: no-repeat;
    min-height: 500px;
  }
}

</style>    