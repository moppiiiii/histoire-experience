<script setup lang="ts">
import Cat from './Cat.vue'
import { defineComponent } from 'vue'

defineComponent({
  name: 'CatStory'
})
</script>

<template>
  <Story title="🐱 Cat">
    <Cat />
  </Story>
</template>
