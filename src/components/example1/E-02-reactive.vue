<template>
  <div>{{ fullName }}</div>
</template>

<script setup>
import { ref, computed, onMounted } from 'vue'

const firstName = ref('Han seo')
const lastName = ref('Yun')

const fullName = computed(() => `${firstName.value} ${lastName.value}`)

onMounted(() => {
  setTimeout(() => {
    firstName.value = 'HS'
  }, 2000)
})
</script>
