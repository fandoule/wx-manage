<script>
    //刷新当前路由
    export default {
        name: "refresh",
        beforeRouteEnter(to, from, next){
            next(vm=>  vm.$router.replace(from.path));
        }
    }
</script>

<style scoped>

</style>