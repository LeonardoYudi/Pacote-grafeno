<script setup lang="ts">

defineProps<{ text: string }>()

</script>

<template>
  <button class="w-10 h-5 border rounded-md bg-stone-700 text-white">{{ text }}</button>
</template>
