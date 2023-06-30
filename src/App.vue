<template lang="pug">
div.overflow-hidden.w-screen
  SiteNavigation.flex.flex-wrap.w-full
  RouterView
</template>

<script>
  import { RouterView } from 'vue-router'
  import SiteNavigation from '@/components/SiteNavigation.vue'

  export default{
    name: 'app',
    components: {
      SiteNavigation: SiteNavigation
    }
  }
</script>
