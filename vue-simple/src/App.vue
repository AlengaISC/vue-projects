<script>
import FoodItem from './components/FoodItem.vue';

export default {
    data() {
        return {
            message: 'Ola mundo!',
            count: 0,
        };
    },
    components: {
        FoodItem,
    },
};
</script>

<template>
    <h1>{{ message }}</h1>
    <button @click="count++">You clicked me {{ count }} times.</button>
    <FoodItem />
</template>

<style scoped></style>
