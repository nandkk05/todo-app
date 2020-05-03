<template>
  <div>
      <input type="text" class="todo-input" placeholder="what needs to be done?">
      Todo list goes here
  </div>
</template>

<script>
export default {
  name: 'To-do list',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">

.todo-input{
    width: 100%;
    padding: 10px 18px;
    font-size: 18px;
    margin-bottom: 16px;

    &:focus{
        outline: 0;
    }
}

</style>
