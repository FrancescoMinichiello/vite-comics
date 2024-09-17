<script>
export default{
  data(){
    return{
    
    }
  }
}
</script>

<template>
<div class="container-fluid">
    <div class="row py-5 justify-content-around">
        <div class="col d-flex justify-content-center">
            <a href="#"><button class="button-sign-up">SIGN-UP NOW!</button></a>
        </div>
        <div class="col d-flex">
            <p class="d-flex align-items-center me-5"><b>FOLLOW US</b></p>
            <div class="d-flex align-items-center gap-3">
                <a href="#"><img src="../assets/img/footer-facebook.png" alt="Facebook"></a>
                <a href="#"><img src="../assets/img/footer-twitter.png" alt="Twitter"></a>
                <a href="#"><img src="../assets/img/footer-youtube.png" alt="YouTube"></a>
                <a href="#"><img src="../assets/img/footer-pinterest.png" alt="Pinterest"></a>
                <a href="#"><img src="../assets/img/footer-periscope.png" alt="Periscope"></a>
            </div>
        </div>
    </div>
</div>
</template>

<style lang="scss" scoped>
@use 'bootstrap/scss/bootstrap.scss' as *;
.row{
    background-color: #333333;
    p{
        margin: 0;
        color: #587AEE;
    }
    .button-sign-up{
        color: white;
        border: 2px solid #587AEE;
        padding: 10px 20px;
        background-color: transparent;
    }
    img{
        height: 30px;
    }
}
</style>    