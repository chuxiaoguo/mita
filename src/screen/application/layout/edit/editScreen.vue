<template>
    <div class="edit-screen">
        <TopNav></TopNav>
        <div class="block">
            <span class="demonstration">不显示间断点</span>
            <el-slider
            v-model="value6"
            :step="10">
            </el-slider>
        </div>
    </div>
</template>

<script>
import TopNav from '../topNav';

export default {
  data() {
    return {
      value6: 20,
    };
  },
  components: {
    TopNav,
  },
};

</script>

<style>

</style>
