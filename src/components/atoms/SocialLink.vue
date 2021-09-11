<template>
        <a class="social-link" :href="to">
            <img :src="pathIcon(icon)" :alt="name">
        </a>
</template>

<script>
export default {
    props: {
        name: { type: String, required: true },
        icon: { type: String, required: true },
        to: { type: String, required: true }
    },

    methods: {
        pathIcon(icon) {
            return require(`@/assets/images/icons/${icon}`);
        }
    }
};
</script>

<style lang="scss" scoped>
.social-link {
    text-decoration: none;
    background-color: var(--orange);
    width: 47px;
    height: 47px;
    border-radius: 5rem;
    display: grid;
    justify-items: center;
    align-items: center;
    transition: transform 0.2s linear;

    &:hover {
        transform: scale(1.1);
    }

    img {
        width: 23px;
        height: 23px;
    }
}
</style>
