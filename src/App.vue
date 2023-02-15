<template>
	<div class="body">
	  <div class="main">
		<p v-if="isAdmin">Simferopol</p>
		<p v-else>Sevastopol</p>
	  </div>
	</div>
  </template>
  
  <script>
  export default {
	data() {
	  return {
		isAdmin: false,
	  };
	}
  };
  </script>
  