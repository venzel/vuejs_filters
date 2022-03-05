<template>
    <div>
        <Cpf />
        <hr />
        <SpacesWithCommas />
        <hr />
        <WordLength />
    </div>
</template>

<script>
import Cpf from './views/Cpf.vue';
import SpacesWithCommas from './views/SpacesWithCommas.vue';
import WordLength from './views/WordLength.vue';

export default {
    components: { Cpf, SpacesWithCommas, WordLength },
};
</script>

<style></style>
