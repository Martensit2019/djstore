<template>
  <the-header />
  <the-breadcrumbs />

  <router-view v-slot="{ Component }">
    <Suspense>
      <div>
        <component :is="Component" />
      </div>
    </Suspense>
  </router-view>
  <the-footer />
</template>

<script>
import TheBreadcrumbs from './components/TheBreadcrumbs.vue'
import TheHeader from './components/TheHeader.vue'
import TheFooter from './components/TheFooter.vue'
export default {
  components: {
    TheHeader,
    TheBreadcrumbs,
    TheFooter,
  },
}
</script>
