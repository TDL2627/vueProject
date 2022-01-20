<template>
     <div id="todo">
    <input type="checkbox" id="todo-item" />
    <label for="todo-item">My Todo Item1</label>
    <input type="checkbox" id="todo-item1" />
    <label for="todo-item1">My Todo Item2</label>
    <input type="checkbox" id="todo-item2" />
    <label for="todo-item2">{{label}}</label>
  </div>
</template>

<script>
export default {
     props: {
      label: { required: true, type: String },
      done: { default: false, type: Boolean }
    }
};
</script>
<style scoped>

#todo{
    background-color: green;
}
</style>