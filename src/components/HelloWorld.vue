<template>
  <div class="hello">
    <div>
      <baidu-map class="bm-view" :center="center" :zoom="zoom"></baidu-map>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
    data() {
      return {
        msg: 'Welcome to Your Vue.js App',
        center: {
          lng: 110,
          lat: 40.059251
        },
        zoom:10
      }
    }
  }

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1,
  h2 {
    font-weight: normal;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
  }

.bm-view {
  width: 300px;
  height: 300px;
}

</style>
