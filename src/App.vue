<script>
import Employee from './components/Employee.vue'
export default {
  components: {
    Employee
  },
  data() {
    return {
      name: '"Эльдар"',
      surn: 'Темиров',
      age: 19,
      value: true,
    }
  }
}
</script>

<template>
  <Employee :name="name" :surn="surn" :age="age" :value="value" />
</template>

<style>

</style>