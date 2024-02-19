<template>
  <h2>Info Personal:</h2>
  <h3>{{ nombre }} <br> {{ mat }} <br> {{ gp }}</h3>
</template>

<script>
  export default{
      data() {
        return{
        nombre : "Jesús Javier Zermeño Rodríguez",
        mat : "20997",
        gp : "5°A"
      }
    }
  }
</script>