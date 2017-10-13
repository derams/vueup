<template>
  <div id="app">

    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>
<style>
  #app{
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: space-around;
    flex-direction: column;
    align-items: center;
    background-color: teal;
  }
</style>
