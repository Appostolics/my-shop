<template>
    <div class="product-list">
        <ProductCard
            v-for="product in products"
            :key="product.id"
            :name="product.name"
            :description="product.description"
            :price="product.price"
            :image="product.image"
        />
    </div>
</template>
<script>
import ProductCard from './ProductCard.vue'
export default {
components: {
ProductCard,
},
props:{
    products:{
        type:Array,
        required:true,
        },
    },
}
</script>
<style scoped>
    .product-list {
        display: flex;
        flex-wrap: wrap;
        gap: 20px;
        justify-content: center;
        
    }
    .buy-button {
		background: #007bff;
		color: #fff;
		font-weight: bold;
		border: none;
		border-radius: 6px;
		padding: 10px 20px;
		cursor: pointer;
		margin-bottom: 20px;
	}

	.buy-button:hover {
		background: #0056b3;
	}
    .price {
		font-size: 18px;
		font-weight: bold;
		color: #28a745;
	}
</style> 