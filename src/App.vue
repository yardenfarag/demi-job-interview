<template>
  <section>
    <app-header />
    <main-content />
    <app-footer />
  </section>
</template>

<script>

import appHeader from './cmps/app-header.cmp.vue'
import appFooter from './cmps/app-footer.cmp.vue'
import mainContent from './cmps/main-content.cmp.vue'

export default {
  components: {
    appHeader,
    appFooter,
    mainContent
  },
}
</script>