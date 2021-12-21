<template>
  <div class="hello">
         <p>{{ hello }}</p>
    <h1>{{ msg }}</h1>
    <p>{{paragraph}}</p>
  </div>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
    hello: String,
    paragraph:String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 20px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}

</style>
