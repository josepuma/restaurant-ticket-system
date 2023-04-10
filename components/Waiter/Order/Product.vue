<template lang="pug">
.relative.border.border-gray-100.bg-white.p-6.rounded-xl
    p.font-medium.text-sm.text-slate-800 Caldo de gallina
    p.text-sm.text-indigo-500.font-medium $ 25.00
    .mt-3.flex.items-center.border.border-slate-200.rounded-xl.w-36
        button.w-10.h-10.text-slate-600 &minus;
        input.w-16.h-10.border-transparent.text-center(type="number", value="1")
        button.w-10.h-10.text-slate-600 &plus;
</template>