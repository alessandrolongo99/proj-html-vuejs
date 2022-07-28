<template>
  <footer>
    <FooterNewsletter />
    <FooterPartners />
  </footer>
</template>

<script>
import FooterNewsletter from './FooterNewsletter.vue'
import FooterPartners from './FooterPartners.vue'

export default {
name: 'AppFooter',
components: {
    FooterNewsletter,
    FooterPartners,
},
}
</script>

<style lang="scss" scoped>
</style>