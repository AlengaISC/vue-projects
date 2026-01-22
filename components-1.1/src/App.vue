<script>
export default {
    data() {
        return {
            message: 'ola mundo',
            count: 0,
        };
    },
    methods: {
        toggleCaps() {
            this.message =
                this.message[0] === 'o' ? this.message.toUpperCase() : this.message.toLowerCase();
        },
    },
};
</script>

<template>
    <h1>{{ message }}</h1>
    <button @click="toggleCaps">Toggle caps</button>
</template>

<style scoped></style>
