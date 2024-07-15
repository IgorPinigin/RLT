<template>
		<div class="main">
				<div class="grid">
				<InventoryCell v-for="cell, index in 25"> 0 </InventoryCell>
		</div>
  </div>
</template>


<script>
import InventoryCell from ".components/InventoryCell.vue";
export default{
	components: {
		InventoryCell,
  },
}
</script>

<style scoped>

</style>