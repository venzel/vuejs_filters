<template>
    <div>{{ word | replaceSpacesWithCommas }}</div>
</template>

<script>
export default {
    data() {
        return {
            word: 'isso vai ficar tudo ok',
        };
    },
    filters: {
        replaceSpacesWithCommas(value) {
            return value.replace(/\s/g, ',');
        },
    },
};
</script>

<style></style>
