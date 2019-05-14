<template>
  <div>
    <el-form label-width="100px">
      <el-form-item label="长度">
        <el-input v-model="chang"></el-input>
      </el-form-item>
      <el-form-item label="宽度">
        <el-input v-model="kuan"></el-input>
      </el-form-item>
    </el-form>
  </div>
</template>
<script>
export default {
    data(){
        return {
            chang: "",
            kuan: "",
        }
    }
};
</script>

