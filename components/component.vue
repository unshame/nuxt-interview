<script setup lang="ts">
const { data } = await useFetch('/api/test');
</script>

<template>{{ data.message }}</template>
