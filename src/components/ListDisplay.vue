<template>
    <ul>
        <li :key="item" v-for="item in list">{{ item }}</li>
    </ul>
</template>

<script>
    export default {
        name: "ListDisplay",
        props: ['list']

    }
</script>

<style scoped>

</style>