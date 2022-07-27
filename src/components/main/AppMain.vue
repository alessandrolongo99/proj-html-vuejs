<template>
  <main>
    <MainCourses />
    <MainEvents />
  </main>
</template>

<script>
import MainCourses from './sections/MainCourses.vue'
import MainEvents from './sections/MainEvents.vue'

export default {
    name: 'AppMain',
    components: {
        MainCourses,
        MainEvents,
    }
}
</script>

<style lang="scss" scoped>

</style>