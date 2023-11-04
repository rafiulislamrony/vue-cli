<template>
  <h1>{{ msg }}</h1>

  <contact-details
    v-for="contact in contacts"
    :key="contact.name"
    :name="contact.name"
    :webAddress="contact.webAddress"
    :address="contact.address"
  >
  </contact-details>
 
</template>

<script>
import ContactDetails from "./ContactDetails.vue";

export default {
  data() {
    return {
      msg: "Welllcome to my website",
      contacts: [
        {
          name: "sheab",
          webAddress: "rrr.com",
          address: "Natore",
        },
        {
          name: "aka",
          webAddress: "aka.com",
          address: "Bonpara",
        },
        {
          name: "Tisha",
          webAddress: "tisha.com",
          address: "Pabna",
        },
      ],
    };
  },
  components: {
    ContactDetails,
  },
};
</script>
