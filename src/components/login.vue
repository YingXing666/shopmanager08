<template>
  <el-form label-position="top" label-width="80px" :model="formdata">
    <el-form-item label="用户名">
      <el-input v-model="formdata.name"></el-input>
    </el-form-item>
    <el-form-item label="密码">
      <el-input v-model="formdata.password"></el-input>
    </el-form-item>
      <el-button type="success">登录</el-button>
  </el-form>
  
</template>

<script>
export default {
  data(){
    return{
      formdata:{
        name:'',
        password:''
      }
    }
  }
};
</script>

<style>
</style>
