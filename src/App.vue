<template>
	<div class="body">
	  <div class="main">
		<p v-if="visible">KIPU</p>
	  </div>
	  <div class="main">
		<p v-if="!visible">KIPU</p>
	  </div>
	</div>
  </template>
  
  <script>
  export default {
	data() {
	  return {
		visible: true,
	  };
	},
  };
  </script>
  