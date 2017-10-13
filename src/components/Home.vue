<template>
  <div class="hello">
    <div class="login">
      你是
      <div class="input-wrap">
        <input type="text" v-modal="massage" placeholder="你的名字">
      </div>
    </div>
    

  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .hello{
    display: flex;
    justify-content: center;
    width: 60%;
    background-color: white;
    line-height: 50px;
  }
  .login{
    display: flex;
    justify-content: center;
    background-color: white;
    line-height: 50px;
  }
  .input-wrap{
    margin-left: 20px;
  }
  input{
    border:0;
    border-bottom: 2px solid cyan;
    outline: 0;

  }
</style>
