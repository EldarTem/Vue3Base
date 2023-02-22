<script>
export default {
  data() {
    return {
      message: 'Эльдар',
      number: 'Темиров',
    }
  },
  methods: {
  }
}
</script>
<template>
  <input class="text-field__input" v-model="message">
  <p :style="{ textTransform: 'uppercase' }">{{ message }}</p>
  <br>
  <input class="text-field__input" v-model="number">
  <p>{{ number * number }}</p>
</template>
<style>

</style>