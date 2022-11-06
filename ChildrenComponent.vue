<template>
<div>Children component - {{ someString }}</div>
</template>

<script setup lang="ts">
import {defineProps} from "vue";

defineProps<{
    someString: string,
    someBoolean: boolean
}>()
</script>

<style lang="scss" scoped>

</style>