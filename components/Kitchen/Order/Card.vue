<template lang="pug">
.rounded-xl.border.bg-white.transition-all(class="hover:drop-shadow-xl")
    .bg-indigo-500.rounded-t-xl.py-4.px-6
        .flex.items-center
            p.text-white.flex-1.font-bold Mesa 5
            .badge.flex-none.animate-pulse.text-white.bg-amber-500.text-xs.px-6.py-2.rounded-xl.font-medium Pendiente
    .p-6
        .divide-y
            KitchenOrderProduct(v-for="i in 5")
        .w-full.bg-slate-100.my-4(class="h-[1px]")
        .flex.gap-4.items-center
            img.h-8.w-8.rounded-full(src="https://images.unsplash.com/photo-1570295999919-56ceb5ecca61?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NHx8YXZhdGFyfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=800&q=60")
            div
                h3.text-slate-700.font-medium.text-sm Manuel Sánchez 
                p.text-slate-500.text-sm Lorem ipsum dolor.
            div.flex-1
                h3.text-slate-700.font-medium.text-sm.text-center 10:20
        .w-full.bg-slate-200.my-4(class="h-[1px]")
        .grid.grid-cols-2.mt-4.gap-4
            button.bg-green-500.rounded-xl.font-medium.text-white.py-2.text-xs Finalizar
            button.bg-red-500.rounded-xl.font-medium.text-white.py-2.text-xs Eliminar
</template>