<script>
export default {
    name: 'App',
    data() {
        return {
            message: 'Questo è un messaggio di esempio.'
        }
    }
}
</script>

<template>
    <h1>{{ message }}</h1>
</template>

<style scoped>
h1 {
    color: gold;
}
</style>