<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>Delectus enim saepe et aliquam provident mollitia culpa fugiat distinctio autem nisi numquam blanditiis amet eum neque voluptates qui quaerat, voluptatibus nobis?</p>
    <div>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates voluptatibus fugiat consequuntur ducimus. Officia vel, minus minima, ut non perferendis nulla amet tempore neque distinctio quibusdam temporibus nesciunt. Consequatur, id!</p>
    </div>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
</style>
