<template>
  <div id="app">
    <navbar-desktop class = "uk-visible@l"> </navbar-desktop>
   <navbar-mobile class= "uk-hidden@l"> </navbar-mobile>
    <router-view/>

  <footer-mobile class  = "uk-hidden@l">  </footer-mobile>

  </div>
</template>


<script >
//navbar 
import navbar_d  from '@/components/desktop/navbar.vue'
import navbar_m from '@/components/mobile/navbar.vue'


//footer
import footer_m from '@/components/mobile/footer.vue'
//import footer_d from '@/components/desktop/footer.vue'




export default {

components:{
  'navbar-desktop':navbar_d,
  'navbar-mobile':navbar_m,
  'footer-mobile':footer_m
},

}


</script>
<style lang="less">

</style>
