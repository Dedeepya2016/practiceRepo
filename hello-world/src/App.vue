<template>
<div>
  <div>hello world</div>
  <h2>{{name}}</h2>
  <div v-text="age">
  </div>
</div>
</template>
<script>

export default {
  data(){
    return{
      name: "Dedeepya",
      age:"twenty four",
    }
  }
}
</script>

<style>
#app{
  text-align: center;
}
</style>
