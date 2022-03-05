<template>
    <div>
        <Cpf />
        <hr />
        <SpacesWithCommas />
    </div>
</template>

<script>
import Cpf from './views/Cpf.vue';
import SpacesWithCommas from './views/SpacesWithCommas.vue';

export default {
    components: { Cpf, SpacesWithCommas },
};
</script>

<style></style>
