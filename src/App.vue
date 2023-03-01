<script>
import Employee from './components/Employee.vue'
export default {
  components: {
    Employee
  },
  data() {
    return {
      name: 'Эльдар',
      surn: 'Темиров',
      age: 19,
    }
  }
}
</script>

<template>
  <Employee :name="name" :surn="surn" :age="age" />
</template>

<style>

</style>