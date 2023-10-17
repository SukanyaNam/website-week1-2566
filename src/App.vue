<template>
  <img src="./assets/logo.png" alt="" />
  <div class="text1">
    <h1>Hello {{name}} </h1>
  </div>
</template>

<script>
  export default{
    data(){
      return { 
        name:"Mark", 
        age:"45" };

    }
  }
</script>

<style>
h1{
  color: blueviolet;
}
.text1{
  font-size: 30px;
}
</style>