<template>
  <img alt="Vue logo" src="./assets/nnn.jpg">

  <div class="menu">
    <a v-for="a in 메뉴들" :key="a">{{ a }} </a>

  </div>

  <div>
    <h4>{{ products[0] }}</h4>
    <p>과제하기</p>
    <p>코딩공부하기</p>
    <p>코딩하기</p>
  </div>
  <div>
    <h4>{{ products[1] }}</h4>
    <p>밥먹기</p>
  </div>
  <div>
    <h4>{{ products[2] }}</h4>
    <p></p>
  </div>
</template>

<script>


export default {
  name: 'App',
  data() {
    return {
      products : ['일1','일2','일3'],
    }
  },
  components: {
   
  }

</script>

<style>
body{
  margin: 0;
}
div {
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>
