<template>
  <h1> {{ msg }}</h1>
  
  <contact-details> </contact-details>

</template>

<script>
import ContactDetails from './ContactDetails.vue'

export default {
  data(){
      return{
          msg: "Welllcome to my website"
      };
  }, 
  components:{
    ContactDetails
  }
}

</script>