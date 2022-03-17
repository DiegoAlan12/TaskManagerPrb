<template>
  <h1>Hello world from vue</h1>
  <input type="text" v-model="name">

  <Task :name="name"/>

</template>

<script>

import Task from "../components/Task.vue";

export default {
  name: 'Home',
  components: {
    Task
  },
  data(){
    return{
      name: ''
    }
  }
}
</script>
