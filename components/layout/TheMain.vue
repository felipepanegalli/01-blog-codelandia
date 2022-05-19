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
    min-height: calc(100vh - 240px);
}

@media (min-width: 992px) {
    main {
        width: 900px;
        margin: 0 auto;
    }
}
</style>