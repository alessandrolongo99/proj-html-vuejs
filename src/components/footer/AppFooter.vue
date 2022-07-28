<template>
  <footer>
    <FooterNewsletter />
  </footer>
</template>

<script>
import FooterNewsletter from './FooterNewsletter.vue'

export default {
name: 'AppFooter',
components: {
    FooterNewsletter,
},
}
</script>

<style lang="scss" scoped>
footer{
    background-color: #e56768;
}
</style>