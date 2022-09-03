<template>
  <card-page />
</template>

<script setup>
import foo from '@foo'
import { msg as virtualMsg } from '@virtual-file'
import { reactive, defineAsyncComponent } from 'vue'
import Button from '../components/button'
import CardPage from '../components/CardPage.vue'
const ImportType = load('ImportType')
const Foo = defineAsyncComponent(() => import('../components/Foo').then((mod) => mod.Foo))
function load(file) {
  return defineAsyncComponent(() => import(`../components/${file}.vue`))
}
const url = import.meta.env.SSR ? import.meta.url : document.querySelector('.import-meta-url')?.textContent
const protocol = url ? new URL(url).protocol : undefined

const state = reactive({
  count: 0,
  protocol,
  url,
})
</script>

<style scoped>
</style>
