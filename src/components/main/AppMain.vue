<template>
  <main>
    <MainCourses />
    <MainEvents />
    <MainLatest />
  </main>
</template>

<script>
import MainCourses from './sections/MainCourses.vue'
import MainEvents from './sections/MainEvents.vue'
import MainLatest from './sections/MainLatest.vue'

export default {
    name: 'AppMain',
    components: {
        MainCourses,
        MainEvents,
        MainLatest,
    }
}
</script>

<style lang="scss" scoped>

</style>