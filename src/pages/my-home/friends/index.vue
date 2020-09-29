<template>
<div class="friends">
    <div calss="friends-title">
        <div class="el-icon-arrow-left"></div>
        <div>我的好友</div>
    </div>
</div>
</template>

<script>
import Vue from 'vue'
import {
  Button
} from 'element-ui'
Vue.use(Button)

export default {
  name: 'friends',
  data () {
    return {
      msg: ''
    }
  },
  mounted: {
    add () {
      console.log(12)
    }
  }
}
</script>

<style scoped>
.friends {
    width: 23.4375rem;
    height: 23.4375rem;
    background-color: #fff;
}

.friends-title {
    width: 100%;
    line-height: 80px;
    background: red;
    display: inline-flex;
    justify-items: flex-end;
}

span {
    flex: 1
}
</style>
