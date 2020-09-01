<template>
  <div class="appfooter">
    <div class="foo">
      <div class="foolist">
        <ul>
          <li>技术信息反馈weibo: 大家好我是酱汁叔</li>
          <li>技术反馈weixin：824365307</li>
          <li>技术反馈PHONE：17826005656</li>
        </ul>
      </div>
      <div class="foolist">
        <ul>
          <li>艺之星有限公司</li>
          <li>shego科技有限公司</li>
          <li>江苏省丹阳市文艺部</li>
        </ul>
      </div>
    </div>
          <p style="font-size:14px;text-align:center">Copyright © 2020 xujunbo
Powered by vue</p>
  </div>
</template>

<script>
export default {
  name: 'app-footer',
  data() {
    return {
    };
  },
  computed:{
  },
  watch:{
  },
  methods: {},
};
</script>

<style scoped>
  *{
    padding: 0;
    margin: 0;
  }
  .appfooter{
    height:240px;
    min-height: 200px;
    width: 100%;
    min-width: 600px;
    margin: auto;
    margin-bottom: -50px;
    font-size: 20px;
    font-weight: 600;
    line-height: 65px;
    background-color: #F4F0EB;
    color:black ;
    padding-bottom: 15px;
    /* position: fixed; */
  }
  .foo{
    display: flex;
    justify-content: space-around;
    align-items: center;
  }
  .foolist{
    width: 300px;
    font-size: 15px;
    font-family: Graphik,Helvetica,Arial,sans-serif;
    font-weight: 300;
    color: #181818;
    text-align: center;
  }
  .foolist >ul{
    list-style: none;
  }
</style>
