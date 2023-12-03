<script setup>
	
import {ref} from 'vue'
import ElementTile from '../ElementTile.vue'

const props = defineProps({

})
const hydrogen = {
	name: "Hyrdogen"
}
</script>

<style>
	.div-container {
		display: flex;
		width: 100%;
		height: 50%;
		flex-direction: column;
		align-items: left;

	}
</style>

<template>
	<div class="div-container">
		<ElementTile :name="hydrogen.name" symbol="H" weight=1.00794 protons=1 />
		<ElementTile name="Lithium" symbol="Li" weight=6.941 protons=3 />
		<ElementTile name="Sodium" symbol="Na" weight=22.98976928 protons=11 />
		<ElementTile name="Potassium" symbol="K" weight=39.0983 protons=19 />
		<ElementTile name="Ruhbidium" symbol="Rb" weight=85.4678 protons=37 />
		<ElementTile name="Cessium" symbol="Cs" weight=132.9054519 protons=0 />
		<ElementTile name="Francium" symbol="Fr" weight=0.000 protons=0 />
	</div>
</template>