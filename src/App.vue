<template>
    <div>
        <Navbar />
        <RouterView/>
    </div>
</template>
<script>
import Navbar from './views/Navbar.vue';
import { RouterView } from 'vue-router';
export default {
    components: {
        Navbar,
    },
};
</script>
<style lang="scss" scoped></style> 