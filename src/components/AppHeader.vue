<script>
export default {
    name: 'AppHeader',
    data() {
        return {
            txt: 'Im the header'
        }
    },
    methods: {
        clickBtn() {
            console.log('');
        }
    }
}
</script>

<template>
    <p>Cover image</p>
    <h2>{{ txt }} !!!</h2>
    <p>Angelo</p>
</template>

<style scoped>
h2 {
    color: green;
}
</style>