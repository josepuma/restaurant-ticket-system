 <script lang="ts" setup>

definePageMeta({
  layout: "garzon",
});

</script>

<template lang="pug">
div
    .py-4
        .grid.grid-cols-1.gap-2(class="md:grid-cols-2 lg:grid-cols-4")
            WaiterOrderProduct(v-for="i in 4")
</template>

