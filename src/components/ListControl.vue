<template>
    <div class="wrapper">
        <input type="text" v-model="value">
        <button @click="changeList">Добавить</button>
    </div>
</template>

<script>
    export default {
        name: "ListControl",
        data() {
            return {
                value: ''
            }
        },
        methods:{
            changeList() {
                if(this.value){
                    this.$emit('changeList', this.value)
                }
            }
        }
    }
</script>

<style scoped>

</style>