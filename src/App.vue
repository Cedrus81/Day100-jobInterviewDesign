
<template>
<app-header />
<main-page />
<app-footer />
</template>

<script>
import appHeader from './components/app.header.vue'
import mainPage from './views/main.page.vue'
import appFooter from './components/app.footer.vue'
export default{
  components: {
    appHeader,
    appFooter,
    mainPage
  }
}
</script>