<template lang="pug">
div
    header.bg-gray-50(aria-label='Page Header')
        .mx-auto.max-w-screen-xl.px-4.py-8(class='sm:py-12 sm:px-6 lg:px-8')(class='sm:flex sm:items-center sm:justify-between')
            .text-center(class='sm:text-left')
                h1.text-2xl.font-bold.text-gray-900(class='sm:text-3xl')
                    | Bienvenido de vuelta, Manuel!
                p.text-sm.text-gray-500(class='mt-1.5')
                    | Creemos un nuevo pedido
            .mt-4.flex.flex-col.gap-4(class='sm:mt-0 sm:flex-row sm:items-center')
                //-button.inline-flex.items-center.justify-center.rounded-lg.border.border-gray-200.bg-white.px-5.py-3.text-gray-500.transition(class='hover:text-gray-700 focus:outline-none focus:ring', type='button')
                    span.text-sm.font-medium  View Website 
                    svg.h-4.w-4(xmlns='http://www.w3.org/2000/svg', class='ml-1.5', fill='none', viewBox='0 0 24 24', stroke='currentColor', stroke-width='2')
                        path(stroke-linecap='round', stroke-linejoin='round', d='M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14')
                button.block.rounded-lg.bg-indigo-600.px-5.py-3.text-sm.font-medium.text-white.transition(class='hover:bg-indigo-700 focus:outline-none focus:ring', type='button')
                    | Crear Pedido
    .container.mx-auto.px-4
        slot
</template>