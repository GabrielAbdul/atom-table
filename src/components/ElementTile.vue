<script setup>
	
import {ref} from 'vue'

const props = defineProps({
	name: String,
	symbol: String,
	weight: Number,
	protons: Number,
	electrons: Number,
	neutrons: Number,
})

</script>

<style>
	.container {
		display: flex;
	}
	.element-card {
		border: thin solid black;
		border-radius: 9px;
		background-color: #FF6A6A;
		color: black;
		width: 100%;

	}

	.text {
	}
</style>

<template>
	<div class="container">
		<div class="element-card">
			<h3 class="text">{{ name }}</h3>
			<h3 class="text">{{ symbol }}</h3>
			<h3 class="text">{{ weight }}</h3>
			<h3 class="text">{{ protons }}</h3>
			<h3 class="text">{{ electrons }}</h3>
			<h3 class="text">{{ neutrons }}</h3>
		</div>
	</div>
</template>