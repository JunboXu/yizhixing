<template>
  <div class="main">
      <!-- <p>让我们开始吧！</p> -->
    <app-header v-if="headerShow"></app-header>
    <div class="container">
        <keep-alive>
            <router-view></router-view>
        </keep-alive>
    </div>
    <app-footer v-if="footerShow"></app-footer>
  </div>
</template>

<script>
import appheader from '../layout/app-header'
import appfooter from '../layout/app-footer'
export default {
  name: 'index',
  data() {
    return {
        headerShow:true,
        footerShow:true
    };
  },
  components:{
      'app-header' : appheader,
      'app-footer' : appfooter
  },
  computed:{
  },
  watch:{
  },
  methods: {},
};
</script>

<style scoped>
* {
    padding: 0;
    margin: 0 auto;
}
.main{
    width: 90%;
    min-width: 1000px;
}
</style>
