<template>

  <header>
    <TheNavigation />
  </header>

    <RouterView :key="$route.fullPath"/>

</template>

<script>
import TheNavigation from './components/TheNavigation.vue'

export default {
    components: {TheNavigation}
}
</script>