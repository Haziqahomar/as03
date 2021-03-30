<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>
      <p class="text-center font-galaxy font-extrabold text-red-400 md:text-red-800 ...">WELCOME TO MY BLOG<br></p>
      <p class="text-center font-sans  text-red-400 md:text-red-800 ...">Nurhaziqah Hazirah binti Omar<br></p>
      <p class="text-center font-sans  text-red-400 md:text-red-800 ...">19FTT1204</p>
      <p class="text-center font-sans  text-red-400 md:text-red-800 ...">DWDT05</p>
      <br>
      <p class="text-center font-serif  text-gray-500 md:text-gray-800 ...">"THE GREATEST GLORY IN LIVING LIES NOT IN NEVER FALLING, BUT IN RISING EVERY TIME WE FALL"</p>
   </h3>

     
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
