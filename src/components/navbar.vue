<template>
<nav>


    <ul>
  <li><a href="#home">Home</a></li>
  <li><a href="#news">News</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#about">About</a></li>
</ul>
</nav>
</template>
<script>
export default {
  
}
</script>


<style scoped>
nav{
    background-color: gray;
    width: 100%;
    position: fixed;
    top: 0;
    padding: 10px;
    left: 0;
}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

li {
  display: inline;
  background-color: greenyellow;
  color: white;
  margin: 10px;
}
a{
    text-decoration: none;
}
</style>