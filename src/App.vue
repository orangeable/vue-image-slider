<template>
	<div id="app">
		<ImageSlider />
	</div>
</template>

<script>
	import ImageSlider from "./components/ImageSlider.vue";
	
	export default {
		name: "App",
		components: {
			ImageSlider
		}
	};
</script>

<style>
	div#app {
		font-family: Arial, sans-serif;
		color: #2c3e50;
		text-align: center;
		margin-top: 60px;
	}
</style>