<template>
    <header>
        <div class="title-box">
            <p>PaneDev</p>
            <p>Blog</p>
        </div>
        <div class="search-box">
            <i class="bi bi-search"></i>
            <input type="search" class="search-input" placeholder="Pesquisar no blog">
        </div>
    </header>
</template>

<script setup>
</script>

<style lang="scss" scoped>
header {
    height: 200px !important;
    background: var(--gradient-default);
    padding: 0 20px;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;

    .title-box {
        display: flex;
        justify-content: space-between;
        align-items: center;

        p {
            color: var(--white);
            font-family: var(--font-lexend);
            font-weight: 400;
            font-size: 18px;
            line-height: 22.5px;
        }
    }

    .search-box {
        position: relative;

        i {
            color: var(--white);
            position: absolute;
            top: 12px;
            left: 12px;
            font-size: 14px;
        }

        .search-input {
            width: 100%;
            border: none;
            height: 20px;
            padding: 20px 40px;
            border-radius: 6px;
            background-color: rgba($color: #FFFFFF, $alpha: .3);
            font-family: var(--font-inter);
            color: rgba($color: #FFFFFF, $alpha: 1);
            font-size: 14px;
            outline: none;

            &::placeholder {
                color: rgba($color: #FFFFFF, $alpha: .5);
            }
        }
    }
}
</style>