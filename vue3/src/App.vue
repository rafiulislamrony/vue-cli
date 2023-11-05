<template>
  <h1>{{ msg }}</h1>

  <my-card cardTitle="About Me">
    <p>Hi its me Rafiul Islam.....</p>
  </my-card>

  <my-card cardTitle="iphone 12">
    <img
      src="https://static-01.daraz.com.bd/p/4067a01b45caf7e0eb593a884b50dd35.jpg_300x0q75.webp"
      alt="" />
    <p>hi mdsh jf jhgbvd njsg jgdbsfds</p>
  </my-card>

  <my-card cardTitle="service"> </my-card>

</template>

<script>
import MyCard from "./MyCard.vue";

export default {
  data() {
    return {
      msg: "Welllcome to my website",
    };
  },
  components: {
    MyCard,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0px;
  box-sizing: border-box;
}

body {
  font-family: sans-serif;
  line-height: 1.8;
}
</style>
