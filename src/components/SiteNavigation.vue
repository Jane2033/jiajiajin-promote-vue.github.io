<template lang="pug">
header.absolute.top-0.left-0.w-screen.bg-blue-700
    nav.w-full.flex.flex-row.justify-between.items-center.mx-16.my-8
        routerlink(:to="{ name:'home' }")
            img.h-12(src='/logo.svg' alt='logo')
        ul.flex.flex-row.text-white.justify-between.items-center
            routerlink(:to="{ name:'home' }")
                li.px-4 服務特色
            routerlink(:to="{ name:'home' }")
                li.px-4 服務區域
            routerlink(:to="{ name:'home' }")
                li.px-4 服務評價
</template>

<script setup>
import { RouterLink } from 'vue-router'

</script>
