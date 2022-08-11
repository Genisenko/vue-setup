<template>
  <div>
    <label for="todo-item">My To-Do Item</label>
    <input type="checkbox" id="todo-item">


    <h1>Message: {{ msg }}</h1>


  </div>
  
</template>

<script>
export default {
    data() {
        return{
            msg: "This is a text interpolation",
        }
  }

}
</script>

<style>

</style>