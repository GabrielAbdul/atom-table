<script setup>
	
import {ref} from 'vue'
import HydroGroup from './groups/HydroGroup.vue'

const props = defineProps({

})

</script>

<style>
	.container {
		display: flex;
		flex-direction: row;
		flex-wrap: nowrap;
		justify-content: center;
	}

	.group-1 {

	}
	.group-2 {

	}
</style>

<template>
	<div class="container ">
		<HydroGroup class="group-1" />
		<HydroGroup class="group-2" />
		<HydroGroup class="group-2" />
		<HydroGroup class="group-2" />
		<HydroGroup class="group-2" />
		<HydroGroup class="group-2" />
		<HydroGroup class="group-2" />
		<HydroGroup class="group-2" />
		<HydroGroup class="group-2" />
		<HydroGroup class="group-2" />
		<HydroGroup class="group-2" />
		<HydroGroup class="group-2" />
		<HydroGroup class="group-2" />
		<HydroGroup class="group-2" />
		<HydroGroup class="group-2" />
		<HydroGroup class="group-2" />
		<HydroGroup class="group-2" />
		<HydroGroup class="group-2" />
		<HydroGroup class="group-2" />
	</div>
</template>