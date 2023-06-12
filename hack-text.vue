<template>
    <vue-hacker-text text="slept@slept.black" />
</template>

<script>
    import Vue from 'vue';
    import VueHackerText from 'vue-hacker-text';

    export default Vue.extend({
        components: {
            VueHackerText
        },
    });
</script>

<style>
    .hacker-text {
        font-weight: 600;
        font-size: 2em;
        color: red;
    }
</style>