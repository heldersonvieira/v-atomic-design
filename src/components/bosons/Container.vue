<template>
        <div class="container">
            <slot />
        </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
.container {
    width: 85%;
    max-width: 1150px;
    margin: 0 auto;
    display: grid;
    gap: 5rem;
}
</style>
