
<template>
    <div class="tutu-content">
        <slot></slot>
    </div>
</template>

<script>
  export default {
    name: 'TutuContent'
  }
</script>

<style lang="scss" scoped>
    .tutu-content {
        flex-grow: 1;
    }
</style>