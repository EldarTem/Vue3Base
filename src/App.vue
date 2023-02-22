<script>
export default {
  data() {
    return {
      isValid: true,
      isDisabled: true,
    }
  }
}
</script>
<template>
	<p :class="{ active: true, error: false }">кипу</p>
</template>
<style>

</style>