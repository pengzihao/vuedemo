<template>
  <div>
    <h1> This is Home Page </h1>
    <!--<h1> This is First Page </h1>-->
    <!--<h1> This is Second Page </h1>-->
    <router-link id="FirstPart" to="/Home">FirstPart</router-link>
    <router-link id="SecondPart" to="/Home/SecondPart">SecondPart</router-link>
    <hr>
    <router-view></router-view>
  </div>
</template>

<script>
    export default {
        name: 'Home'
    }
</script>

<style scoped>

</style>
