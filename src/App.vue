<script>

import AppHeader from './components/AppHeader.vue'
import AppJumbo from './components/AppJumbo.vue'
import AppFooter from './components/AppFooter.vue'
import AppIcons from './components/AppIcons.vue'
import AppSignUpBanner from './components/AppSignUpBanner.vue'

export default {
  components: {
    AppHeader,
    AppJumbo,
    AppFooter,
    AppIcons,
    AppSignUpBanner
  }
}
</script>

<template>
  <AppHeader />
  <main>

    <AppJumbo />
    <AppIcons />
  </main>
  <footer>
    <AppFooter />
    <AppSignUpBanner />
  </footer>
</template>

<style></style>
