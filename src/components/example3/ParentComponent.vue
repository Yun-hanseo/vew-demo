<template>
  <div>
    <ChildComponent
        :message="parentMessage"
        @custom-event="handleEvent"
    />
  </div>
</template>

<script setup>
import { ref, defineOptions } from 'vue'
import ChildComponent from './ChildComponent.vue'

defineOptions({
  name: 'E05ParentComponent'
})

const parentMessage = ref('Hello from parent')

const handleEvent = (payload) => {
  console.log(payload)
}
</script>
