<template>
    <div class="g-button-group">
        <slot></slot>
    </div>

</template>

<script>

</script>

<style lang="scss">
.g-button-group{
    display: inline-flex;
    vertical-align: middle;
    > .g-button{
        border-radius: 0;
        margin-left: -1px;
        &:first-child{
            border-top-left-radius: var(--bordor-radius);
            border-bottom-left-radius: var(--bordor-radius);
        }
        &:last-child{
            border-top-right-radius: var(--bordor-radius);
            border-bottom-right-radius: var(--bordor-radius);
        }
        &:hover{
            position: relative;z-index: 1;
        }
    }
}
</style>