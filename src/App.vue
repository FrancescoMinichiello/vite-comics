<script>
//1-IMPORTO IL COMPONENTE DAI COMPONENTI
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppFooterSocialBanner from './components/AppFooterSocialBanner.vue';
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
    AppFooterSocialBanner
  }
}
</script>

<template>
  <!--INSERISCO I COMPONENTI DOVE VOGLIO CHE SIANO VISIBILI TRAMITE SELF CLOSING TAG | **** "  <componente/>  " **** | -->
  <!--Header-->
  <AppHeader/>
  <AppMain/>
  <AppFooter/>
  <AppFooterSocialBanner/>
</template>

<style lang="scss" scoped>

</style>    
