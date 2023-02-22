<script>
export default {
  data() {
    return {
      language: '',
      visible: false,
      visible1: false,
      visible2: false,
    }
  },
  methods: {
    one() {
      this.visible = true;
    },
    two() {
      this.visible1 = true;
    },
    three() {
      this.visible2 = true;
    }
  }
}
</script>
<template>
      <input type="radio" v-model="language" value="Русский" @click="first">
      <p>Russian</p>
      <p></p>
      <input type="radio" v-model="language" value="Английский" @click="second">
      <p>UK</p>
      <p></p>
      <input type="radio" v-model="language" value="Немецкий" @click="third">
      <p></p>
      <p>Germany</p>
      <p v-if="visible">Привет</p>
      <p v-else-if="visible1">Hello</p>
      <p v-else-if="visible2">Gutten tack</p>

</template>
<style>

</style>