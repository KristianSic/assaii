
<template lang="pug">

h1 {{ msg }}
.card
  button(type='button' @click='count++') count is {{ count }}

</template>

<style lang="less" scoped>
.read-the-docs {
  color: #888;
}
</style>




<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)

</script>
