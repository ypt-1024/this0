<script setup>
import { MdEditor } from 'md-editor-v3';
import 'md-editor-v3/lib/style.css';

const text = ref('# Hello Editor');
</script>

<template>
  <MdEditor v-model="text" />
</template>

<style scoped lang="scss"></style>