<template>
  <div class="profile">
    <img alt="Vue logo" src="./assets/logo.png">
    <h1>陈晓茵-2310274047-作业3</h1>
    <div class="profile-info">
      <p><strong>昵称：</strong> Solar</p>
      <p><strong>学号：</strong> 2310274047</p>
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.profile {
  font-family: Arial, sans-serif;
  text-align: center;
  margin: 20px;
}
.profile h1 {
  font-size: 24px;
  margin-bottom: 10px;
}

.profile-info {
  background-color: #f0f0f0;
  border: 1px solid #ccc;
  padding: 20px;
  border-radius: 5px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.profile-info p {
  font-size: 18px;
  margin: 10px 0;
}

.profile-info strong {
  font-weight: bold;
}
</style>
