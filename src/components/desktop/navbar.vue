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
              <svgicon icon = "home" height="35" width = "40" color = "#FFD700">  </svgicon>
              Home
     
            </div></router-link> </li>
           
            
              <li><router-link to="/">  <div>
              <svgicon icon = "user" height="35" width = "40" color = "#FFD700">  </svgicon> 
               Bio

            </div></router-link> </li>
               <li><router-link to="/">  <div>
              <svgicon icon = "instagram" height="35" width = "40" color = " #FFD700">  </svgicon> 
             Gallery
    
            </div></router-link> </li>

              <li> 

         
                   <a class="uk-button uk-button-default" href=""> About Me</a>
           
              </li>
            
            
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
      brand:'Nd Talks',
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
