<template>
        <div class="social-networks">
            <SocialLink to="https://github.com" icon="github.svg" name="Github" />
            <SocialLink to="https://twitter.com" icon="twitter.svg" name="Twitter" />
            <SocialLink to="https://facebook.com" icon="facebook.svg" name="Facebook" />
        </div>
</template>

<script>
import { SocialLink } from '@/components/atoms';

export default {
    components: { SocialLink },
};
</script>

<style land="scss" scoped>
.social-networks{
    display: grid;  
    gap: 1rem;
}
</style>
