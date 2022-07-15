<template>
    <div class="">
        <list-display :list="list"/>
        <list-control @changeList="changeList"/>
    </div>
</template>

<script>

    import ListControl from "@/components/ListControl";
    import ListDisplay from "@/components/ListDisplay";

    export default {
        name: "ListController",
        components: {
            ListControl, ListDisplay
        },
        methods: {
            changeList(item) {
                this.list.push(item);
            }
        },
        data() {
            return {
                list: []
            }
        }
    }
</script>

<style scoped>

</style>