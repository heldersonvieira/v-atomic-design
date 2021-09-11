<template>
        <div class="presentation">
            <SocialNetworks />

            <img src="@/assets/images/presentation.svg" alt="Apresentação">
        </div>
</template>

<script>
import { SocialNetworks } from '@/components/molecules'

export default {
    components: { SocialNetworks },
};
</script>

<style lang="scss" scoped>
.presentation{
    // max-width: 1300px;
    // margin: 0 auto;
    position: relative;
    display: grid;
    justify-content: center;

    img {
        width: 80%;
        justify-self: center;
    }

    .social-networks {
        position: absolute;
        left: 0;
        top: 50%;
        transform: translateY(-50%);
    }
}
</style>
