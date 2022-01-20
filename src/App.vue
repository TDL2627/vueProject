<template>
<navbar/>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <div id="sex1">
   <h1>To-Do List</h1>
  <ul>
    <li>
      <to-do-item label="My ToDo Item 3"/>
    </li>
  </ul>
  </div>
 
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import ToDoItem from './components/ToDoItem.vue';
import navbar from './components/navbar.vue';


export default {
  name: 'App',
  components: {
    HelloWorld,
    ToDoItem,
    navbar

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
#sex1{
  background-color: red;
  color: white;
}
</style>
