<script>
export default {
  data() {
    return {
      obj: {
        done: true,
        selected: false,
      },
    }
  }
}
</script>
<template>
	<button @click="setDone">click</button>
</template>
<style>

</style>