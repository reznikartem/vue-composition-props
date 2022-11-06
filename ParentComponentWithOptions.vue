<template>
    <children-component />
</template>

<script lang="ts">
import ChildrenComponent from "./ChildrenComponent.vue";
export default {
    name: "ParentComponentWithOptions",
    components: {ChildrenComponent}
}
</script>

<style lang="scss" scoped>

</style>