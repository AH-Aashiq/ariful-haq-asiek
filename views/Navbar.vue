<template>
    <h1>Hello Mother Father</h1>
    <h2>{{ msg }}</h2>
</template>

<script>
export default {
    name: 'Navbar',
    data() {
        return {
            msg: 'Welcome to Your Vue.js App',
        };
    },
};
</script>

<style scoped>
h1,
h2 {
    color: red;
    text-align: center;
    padding: 50px auto;
    font-size: 2em;
}
</style>
