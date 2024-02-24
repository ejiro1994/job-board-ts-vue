<script setup lang="ts">
import { reactive, ref } from 'vue'
const state = reactive({
  name: 'Ejiro',
  age: 29 as string | number
})

const lastName = ref('Akpoduado')

const age = ref<number | string>(29)

const handleButton = () => {
  state.name = 'Tega'
}
</script>

<template>

</template>
