<template>
  <div>
    <img :src="img_url">
  </div>
</template>

<script>
import img_url from "./assets/test.jpg";
export default {
  data(){
    return {
      img_url
    }
  },
  created(){
    console.log(this);
  }
}
</script>

<style>
</style>
