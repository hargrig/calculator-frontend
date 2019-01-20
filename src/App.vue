<template>
	<div id="app">
		<img alt="Vue logo" src="./assets/calc.png">
		<Calculator msg="calculate  what  you  need" /> 
	</div>
</template>

<script>
import Calculator from './components/Calculator.vue'

export default {
	name: 'app',
	components: {
		Calculator
	}
}
</script>

<style>
body {
	background-color: #16141A;
}

#app {
	font-family: 'Rajdhani', sans-serif;
	text-align: center;
	margin-top: 60px;
}
</style>
