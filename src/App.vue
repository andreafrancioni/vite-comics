<script>

import AppHeader from './components/AppHeader.vue'
import AppContent from './components/AppContent.vue'
import AppFooter from './components/AppFooter.vue'
import AppIcons from './components/AppIcons.vue'

export default {
  components: {
    AppHeader,
    AppContent,
    AppFooter,
    AppIcons,
  }
}
</script>

<template>
  <AppHeader />
  <main>

    <AppContent />
    <AppIcons />
  </main>
  <footer>
    <AppFooter />
  </footer>
</template>

<style></style>
