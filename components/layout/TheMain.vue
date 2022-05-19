<template>
    <main>
        <slot></slot>
    </main>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
main {
    padding: 20px;
    background-color: var(--white-200);
    min-height: calc(100vh - 240px);
}
</style>