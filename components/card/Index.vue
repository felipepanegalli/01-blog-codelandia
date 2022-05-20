<template>
    <div class="card">
        <div class="header">
            <p class="date">
                <slot name="date"></slot>
            </p>
            <button @click="changeLike">
                <template v-if="isLiked">
                    <i class="bi bi-heart-fill"></i>
                </template>
                <template v-else>
                    <i class="bi bi-heart"></i>
                </template>
            </button>
        </div>
        <h1 class="title">
            <slot name="title"></slot>
        </h1>
        <div class="body">
            <slot></slot>
        </div>
    </div>
</template>

<script>
export default {
    props: {
        like: {
            type: Boolean,
            default: false
        }
    },

    setup(props) {
        const isLiked = ref(props.like);

        const changeLike = () => {
            isLiked.value = !isLiked.value
        }

        return { isLiked, changeLike }
    }
}
</script>

<style lang="scss" scoped>
.card {
    background-color: var(--white);
    padding: 20px;
    box-shadow: 0px 0px 10px rgba(19, 19, 31, 0.05);
    border-radius: 5px;
    font-family: var(--font-lexend);
    font-weight: 400;
    display: flex;
    flex-direction: column;
    gap: 1rem;
    margin: 15px 0;

    .header {
        display: flex;
        align-items: center;
        justify-content: space-between;

        .date {
            color: var(--gray);
            font-size: 14px;
        }

        button {
            cursor: pointer;
            border: none;
            background: transparent;

            i {
                color: var(--purple);
                font-size: 18px;
            }
        }
    }

    .title {
        font-size: 18px;
        color: var(--gray-dark);
        line-height: 22.5px;
    }

    .body {
        font-size: 14px;
        color: var(--gray);
        line-height: 26px;
    }
}
</style>