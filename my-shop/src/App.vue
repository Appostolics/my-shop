<template>
	<div class="app">
		<ProductList/>
		<ReviewsComponent/>
		<FooterComponent/>
	</div>
</template>

<script>
import ReviewsComponent from './components/ReviewsComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import ProductList from './components/ProductList.vue'; 

export default {
	components:{
		ProductList,
		ReviewsComponent,
		FooterComponent
	}
};
</script> 