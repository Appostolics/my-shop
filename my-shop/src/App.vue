<template>
	<div class="app">
		<ProductList/>
		<FooterComponent/>
	</div>
</template>

<script>
import FooterComponent from './components/FooterComponent.vue';
import ProductList from './components/ProductList.vue'; 
export default {
	components:{
		ProductList,
		FooterComponent
	}
};
</script> 