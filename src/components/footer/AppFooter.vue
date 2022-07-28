<template>
  <footer>
    <FooterNewsletter />
    <FooterPartners />
    <FooterLinks />
  </footer>
</template>

<script>
import FooterNewsletter from './FooterNewsletter.vue'
import FooterPartners from './FooterPartners.vue'
import FooterLinks from './FooterLinks.vue'

export default {
name: 'AppFooter',
components: {
    FooterNewsletter,
    FooterPartners,
    FooterLinks
},
}
</script>

<style lang="scss" scoped>
</style>