<script setup>
import Navbar from './Navbar.vue';
import Table from './Table.vue';
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
<Navbar />
<Table />
</template>

