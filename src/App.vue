<template>
	<div id="app">
		<img alt="Tesla Official Logo" :src="TeslaLogo" />
		<img alt="Model 3" :src="Model3" id="header-img" />
	</div>
</template>

<script>
import Model3 from "./assets/model-3.jpg";
import TeslaLogo from "./assets/tesla.svg";
export default {
	data() {
		return {
			Model3: Model3,
			TeslaLogo: TeslaLogo,
		};
	},
};
</script>

<style>
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}

/* Add styles to the image or convert the image to a background-image*/
</style>
