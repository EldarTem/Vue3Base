<template>
	<div class="body">
	  <div class="main">
		<a :href="page">KIPU</a>
	  </div>
	</div>
  </template>
  
  <script>
  export default {
	data() {
	  return {
		page: "page.html",
	  };
	},
  };
  </script>