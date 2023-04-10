<script lang="ts" setup>

</script>

<template lang="pug">
.py-4
    h2.text-2xl.font-medium.text-slate-700.my-3 Pedidos solicitados
    .grid.grid-cols-1.gap-4(class="md:grid-cols-2 lg:grid-cols-4")
        KitchenOrderCard(v-for="i in 10")
</template>