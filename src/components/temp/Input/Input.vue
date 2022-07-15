<template src="Input.html">
    
</template>

<script>
    export default {
        name: "v-Input",

        methods: {
            changeValue() {
                this.$emit('changeValue',this.value)
            },

            data() {
                return {
                    value: "",
                }
            }
        }
    }
</script>

<style rel="./style.scss">

</style>