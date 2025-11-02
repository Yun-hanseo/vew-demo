<template>
  <div>
    <ChildComponent1 />
  </div>
</template>

<script>
import { provide } from 'vue'
import ChildComponent1 from '@/components/example4/ChildComponent1.vue'

export default {
  name: 'E06ParentComponent',
  components: { ChildComponent1 },
  setup() {
    // ✅ provide를 setup 안에서 사용
    provide('sharedMessage', 'Hello from provide')
  }
}
</script>
