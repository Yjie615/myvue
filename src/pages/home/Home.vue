<template>
	<home-header />
</template>

<script>
import HeaderComponent from './Header'
export default {
	components: {
		'home-header':HeaderComponent
	}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	.text{
		background:red;
	}
</style>
