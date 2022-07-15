<template src="Controller.html">
    
</template>


<script>

    import Display from "@/components/temp/Display/Display";
    import Input from "@/components/temp/Input/Input"

    export default {
        name: "v-Controller",
        components: {
            Display, Input
        },
        data() {
            return {
                value: "",
            }
        },

        methods: {
            changeValue(value) {
                this.value = value;
            }
        }
    }
</script>

<style scoped>

</style>