<template>
        <div class="service">
            <h2 class="title">{{ title }}</h2>
            <p class="description">{{ description }}</p>
        </div>
</template>

<script>
export default {
    props: {
        title: { type: String, required: true },
        description: { type: String, required: true }
    }
};
</script>

<style lang="scss" scoped>
.service{
    .title{
        color: var(--purple);
        font-weight: bold;
        margin-bottom: 0.8rem;
    }

    .description {
        color: var(--gray);
        line-height: 1.5;
    }
}
</style>
