<template>
    <div>
        <div>{{ word }}</div>
        <div>{{ word | countWords }}</div>
        <hr />
        <div>{{ countWordsComputed }}</div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            word: 'isso vai ficar surpreendente',
        };
    },
    filters: {
        countWords(value) {
            return value
                .split(' ')
                .map((e) => `${e} (${e.length})`)
                .join(' ');
        },
    },
    computed: {
        countWordsComputed() {
            return this.word
                .split(' ')
                .map((e) => `${e} (${e.length})`)
                .join(' ');
        },
    },
};
</script>

<style></style>
