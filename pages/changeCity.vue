<template>
  <div class="page-changeCity">
    <el-row>
      <el-col :span="24">
        <iSelect/>
      </el-col>
    </el-row>
    <el-row>
      <el-col :span="24">
        <Hot/>
      </el-col>
    </el-row>
    <el-row>
      <el-col :span="24"></el-col>
    </el-row>
  </div>
</template>

<script>
  import iSelect from '~/components/changeCity/iselect'
  import Hot from '~/components/changeCity/hot.vue'

  export default {
    components: {
      iSelect,
      Hot
    }
  }
</script>

<style>

</style>
