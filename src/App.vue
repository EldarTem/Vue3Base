<template>
	<div class="body">
	  <div class="main">
		<p v-if="!hidden">KIPU</p>
	  </div>
	</div>
  </template>
  
  <script>
  export default {
	data() {
	  return {
		hidden: false,
	  };
	},
  };
  </script>
  