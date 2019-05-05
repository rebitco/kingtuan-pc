<template>
  <el-row :gutter="15">
    <el-col :md="5" :lg="5" :xl="5">
      <div class="grid-content">
        <location></location>
      </div>
    </el-col>
    <el-col :md="13" :lg="13" :xl="13">
      <div class="grid-content">
        <user></user>
      </div>
    </el-col>
    <el-col :md="6" :lg="6" :xl="6">
      <div class="grid-content">
        <nav></nav>
      </div>
    </el-col>
  </el-row>
</template>

<script>
  import Location from './location'
  import Nav from './nav'
  import User from './user'

  export default {
    name: 'index',
    components: {
      Location, Nav, User
    }
  }
</script>

<style scoped>
  @import "/assets/css/public/header.scss";
</style>
