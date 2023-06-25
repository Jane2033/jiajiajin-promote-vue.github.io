<template lang="pug">
div.w-screen
SiteNavigation
</template>

<script>
  import SiteNavigation from './components/SiteNavigation.vue'

  export default{
    name: 'app',
    components: {
      SiteNavigation: SiteNavigation
    }
  }
</script>
