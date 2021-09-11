<template>
        <a class="nav-item" :href="to">
            {{ text }}
        </a>
</template>

<script>
export default {
    props: {
        text: { type: String, required: true },
        to: { type: String, required: true }
    }
};
</script>

<style lang="scss" scoped>
.nav-item {
    color: var(--gray);
    text-decoration: none;
    font-size: 1.3rem;
}
</style>
