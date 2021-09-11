<template>
        <form class="search-form">
            <input type="search" placeholder="Buscar">
            <button type="submit">
                <img src="@/assets/images/icons/search.svg" alt="Buscar">
            </button>
        </form>
</template>

<style lang="scss" scoped>
.search-form {
    position: relative;
    width: max-content;
    
    input {
        border: none;
        border-radius: 1rem;
        padding: 0.5rem 1rem;
        box-shadow: 0px 5px 5px rgba(#000000, 0.08);

        &::placeholder {
            color: var(--light-gray);
        }
    }

    button {
        position: relative;
        right: 17px;
        top: 1px;
        transform: translate(-50%);
        width: 30px;
        height: 30px;
        background: var(--orange);
        border: none;
        border-radius: 5rem;

        img {
            position: relative;
            top: 2px;
        }
    }
}
</style>
