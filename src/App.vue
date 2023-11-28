<script>

import AppHeader from './components/AppHeader.vue'
import AppContent from './components/AppContent.vue'
import AppFooter from './components/AppFooter.vue'
import AppIcons from './components/AppIcons.vue'
import AppSignUpBanner from './components/AppSignUpBanner.vue'

export default {
  components: {
    AppHeader,
    AppContent,
    AppFooter,
    AppIcons,
    AppSignUpBanner
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
    <AppSignUpBanner />
  </footer>
</template>

<style></style>
