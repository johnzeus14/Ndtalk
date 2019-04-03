<template>
 
  <div class="hero">
  
  	<div class="uk-height-large uk-background-cover uk-overflow-hidden uk-light uk-flex uk-flex-top uk-margin-remove-top">
    <div class="uk-width-1-2@m uk-text-center uk-margin-auto uk-margin-auto-vertical">
      

  <form class="uk-grid-small" uk-grid>
  
    <div class="uk-width-1-2@s">
        <input class="uk-input" type="text" placeholder="50">
    </div>
    <div class="uk-width-1-2@s">
        <input class="uk-input" type="text" placeholder="50">
    </div>
</form>
       
    </div>
</div>
  
  </div>
</template>


  
<script>




export default {
  data(){
    return{
   tripType: [1,2,3,4],
   ticketClass: [1,2,3,4],
   travellerDetail:{
     adults: "",
     children: "",
     infants: ""
   },
   flightItineraryDetail: [
     {
       originAirportCode: "",
       destinationAirportCode: "",
       departureDate:""
     } 
   ]





     
    }
  },
methods :{

},
 

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">

// @import '../theme/theme.less';

.hero {
	.uk-background-cover{
		background-image:url('/img/travelss.jpg');
	}
}
</style>
