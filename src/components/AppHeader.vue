<script>
export default{
  data(){
    return{
        navLinks:[
            "Characters",
            "Comics",
            "Movies",
            "Tv",
            "Games",
            "Collectibles",
            "Videos",
            "Fans",
            "News",
            "Shop",
        ]
    }
  }
}
</script>

<template>
    <header>
            <div class="row gx-0 py-3">
                <div class="col d-flex justify-content-center align-items-center">
                    <img src="../assets/img/dc-logo.png" alt="DC logo">
                </div>
                <div class="col d-flex align-items-center">
                    <ul class="d-flex gap-3 fs-5 m-0">
                        <li v-for="navItems in navLinks">{{ navItems }}</li>
                    </ul>
                </div>
            </div>
    </header>
</template>

<style lang="scss" scoped>
@use 'bootstrap/scss/bootstrap.scss' as *;

</style>    