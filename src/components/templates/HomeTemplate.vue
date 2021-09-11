<template>
        <div class="home-template">
            <Container>
                <Header />
                <Presentation />
                <Services />
            </Container>
        </div>
</template>

<script>
import { Container } from '@/components/bosons';
import { Header, Presentation, Services } from '@/components/organisms';

export default {
    components: { Container, Header, Presentation, Services },
};
</script>

<style lang="scss" scoped>
.home-template {
    margin: 5rem auto;
}
</style>
