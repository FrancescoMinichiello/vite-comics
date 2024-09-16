<script>
export default{
  data(){
    return{
      navLinksDcComics:[
        "Characters",
        "Comics",
        "Movies",
        "TV",
        "Games",
        "Videos",
        "News"
      ],
      navLinksShop:[
      "Shop DC",
      "Shop DC Collectibles"
      ],
      navLinksDc:[
      "Terms Of Use",
      "Privacy policy (New)",
      "Ad Choices",
      "Advertising",
      "Jobs",
      "Subscriptions",
      "Talent Workshops",
      "CPSC Certificates",
      "Ratings",
      "Shop Help",
      "Contact Us"
      ],
      navLinksSites:[
      "DC",
      "MAD Magazine",
      "DC Kids",
      "DC Universe",
      "DC Power Visa"
      ],
    }
  }
}
</script>

<template>
  <footer>
    <div class="container-fluid">
      <div class="row row-cols-2">
        <div class="col d-flex footer-links p-5">
          <div class="col footer-nav px-2">
            <p>DC COMICS</p>
            <ul>
              <li v-for="navLink in navLinksDcComics">{{ navLink }}</li>
            </ul>
            <p>SHOP</p>
            <ul>
              <li v-for="navLink in navLinksShop">{{ navLink }}</li>
            </ul>
          </div>
          <div class="col footer-nav px-2">
            <p>DC</p>
            <ul>
              <li v-for="navLink in navLinksDc">{{ navLink }}</li>
            </ul>
          </div>
          <div class="col footer-nav px-2">
            <P>SITES</P>
            <ul>
              <li v-for="navLink in navLinksSites">{{ navLink }}</li>
            </ul>
          </div>
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
  color: white;
  .footer-image{
    background-image: url("../assets/img/dc-logo-bg.png");
    background-repeat: no-repeat;
    min-height: 500px;
  }
  .footer-nav{
    width: calc(100% / 3);
    p{
      font-size: 20px;
    }
  }
}
ul{
  padding-left: 0;
  li{
    padding-bottom: 10px;
  }
}

</style>    