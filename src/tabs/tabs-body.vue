<template>
    <div class="tabs-body">
     <slot></slot>
    </div>
</template>
<script>
    export default {
      name: 'TutuTabsBody',
      inject:['eventBus'],
      created() {
      }
    }
</script>
<style>
    .tabs-body{

    }
</style>