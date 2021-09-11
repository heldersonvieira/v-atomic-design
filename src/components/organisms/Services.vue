<template>
        <div class="services">
            <Service
                title="Front End"
                description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quos iusto, modi atque unde, laborum quasi quibusdam optio dolorum commodi magnam adipisci expedita. Sed rem exercitationem, eos mollitia velit laudantium expedita."
            />

            <Service
                title="Back End"
                description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quos iusto, modi atque unde, laborum quasi quibusdam optio dolorum commodi magnam adipisci expedita. Sed rem exercitationem, eos mollitia velit laudantium expedita."
            />

            <Service
                title="Manutenção"
                description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quos iusto, modi atque unde, laborum quasi quibusdam optio dolorum commodi magnam adipisci expedita. Sed rem exercitationem, eos mollitia velit laudantium expedita."
            />
        </div>
</template>

<script>
import { Service } from '@/components/molecules'

export default {
    components: { Service },
};
</script>

<style lang="scss" scoped>
.services{
    // max-width: 1300px;
    // margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;

    .service {
        width: 25%;
    }
}
</style>
