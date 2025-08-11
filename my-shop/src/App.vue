<template>
	<div class="app">
		<ProductCard
	name="Zeonix"
	description="Класний комп"
	price="47599грн"
	image="https://gamingpc.com.ua/image/cache/770x510/e87fb2ce2e10979423f378d474daa52d.webp"/>
	</div>
	</template>

<script>
import ProductCard from './components/ProductCard.vue';

export default {
	components:{
		ProductCard
	}
};
</script>