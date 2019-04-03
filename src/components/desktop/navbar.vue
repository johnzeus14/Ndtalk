<template>
 
  <div>

    <div uk-sticky="sel-target: .uk-navbar-container; cls-active: uk-navbar-sticky">
    <nav class="uk-navbar-container" uk-navbar>
   

        <div class="uk-navbar-left">
          <div>
            <a class="uk-navbar-item uk-logo" href="#">{{brand}}</a>
        </div>

        </div>

      <div class="uk-navbar-right">
          <div>
            

          
        <ul class="uk-navbar-nav">
            <li><router-link to="/">  <div>
              <svgicon icon = "map-pin" height="35" width = "40" color = "white">  </svgicon>
              Home
     
            </div></router-link> </li>
           
             <li><router-link to="/">  <div>
              <svgicon icon = "correct" height="35" width = "40" color = "white">  </svgicon> 
              Deals
    
            </div></router-link> </li>
              <li><router-link to="/">  <div>
              <svgicon icon = "visa" height="35" width = "40" color = "white">  </svgicon> 
              Visa

            </div></router-link> </li>


              <li> <div>
            <!--  button components is to be here -->

            </div></li>
            
            
        </ul>

        </div>

    </div>
      

</nav>


</div>

   
  
  
  </div>
</template>


  
<script>

import {mapActions} from 'vuex';


export default {
  data(){
    return{
      brand:'Travel PLanner',
    }
  },
methods :{

},
 

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">

// @import '../theme/theme.less';
</style>
