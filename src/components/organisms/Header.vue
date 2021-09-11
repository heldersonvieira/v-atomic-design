<template>
        <header class="header">
            <Logo />
            <NavBar />
            <SearchForm />
        </header>
</template>

<script>
import { Logo } from '@/components/atoms';
import { NavBar, SearchForm } from '@/components/molecules';

export default {
    components: { Logo, NavBar, SearchForm },
};
</script>

<style lang="scss" scoped>
.header{
    // max-width: 1300px;
    // margin: 0 auto;
    display: grid;
    grid-template-columns: 160px repeat(2, auto);
    align-items: center;
    justify-content: space-between;
}
</style>
