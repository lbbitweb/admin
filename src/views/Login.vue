<template>
    <div class="login">
        <el-form ref="form" :model="form">
            <el-form-item>
                <el-input v-model="form.username"></el-input>
            </el-form-item>
        </el-form>
    </div>
</template>
<script>
export default {
    data() {
        return {
            form:{
                username: '',
                password: ''
            }
        }
    },
}
</script>
<style lang="sass" scoped>

</style>

