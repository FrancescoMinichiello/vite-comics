<script>
//1-IMPORTO IL COMPONENTE DAI COMPONENTI
import AppHeader from './components/AppHeader.vue';
import AppJumbotron from './components/AppJumbotron.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppFooterSocialBanner from './components/AppFooterSocialBanner.vue';
import AppBannerMain from './components/AppBannerMain.vue';
export default{
  data(){
    return{

    }
  },
  components:{
    //2-IMPORTO IL COMPONENTE NELLA LISTA DEI COMPONENTI
    AppHeader,
    AppMain,
    AppFooter,
    AppFooterSocialBanner,
    AppBannerMain,
    AppJumbotron
  }
}
</script>

<template>
  <!--INSERISCO I COMPONENTI DOVE VOGLIO CHE SIANO VISIBILI TRAMITE SELF CLOSING TAG | **** "  <componente/>  " **** | -->
  <!--Header-->
  <AppHeader/>
  <AppJumbotron/>
  <AppMain/>
  <AppBannerMain/>
  <AppFooter/>
  <AppFooterSocialBanner/>
</template>

<style lang="scss" scoped>

</style>    
