<template>
    <div class="w-[370px] border border-green-400 shadow-lg mb-8 flex flex-col">
        <img :src="product.thumbnail" class="product-image" alt="">
        <h3 class="p-4 bg-white border-b font-bold border-green-400">{{ product.title }}</h3>
        <div class="flex-1 bg-gray-200">
            <div class="p-4 text-gray-600 italic">{{ product.description }}</div>
        </div>
        <div class="p-4 bg-green-600 text-white">
            <h4 class="text-4xl">
                {{ product.price.toLocaleString(undefined, {"style":"currency","currency":'PHP'}) }}
            </h4>
        </div>
    </div>
</template>

<script setup>

const props = defineProps({
    product: Object
})

</script>

<style scoped>
.product-image {
    width: 100%;
    aspect-ratio: 20/9;
    object-fit: cover;
}
</style>