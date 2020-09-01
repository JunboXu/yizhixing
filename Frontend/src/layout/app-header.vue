<template>
  <div class="appheader">
      <img src="" alt="logo" class="logo">
      <!-- <d>艺之星 丹阳孩童的艺术摇篮</d> -->
      <ul class="navli">
        <li><a href="">关于我们</a></li>
        <li><a href="">课程信息</a></li>
        <li><a href="">学习报名</a></li>
      </ul>

  </div>
</template>

<script>
export default {
  name: 'app-header',
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
  margin:0;
}
a:link
,a:visited
,a:active{color: black;
text-decoration: none;}
a:hover{
  color: bisque;
}
p{
  text-align: center;
  
}
  .appheader{
    height: 65px;
    min-height: 65px;
    width: 100%;
    min-width: 600px;
    margin: 50px auto auto auto;
    
    font-size: 20px;
    font-weight: 1000;
    line-height: 65px;
    background-color: white;
    color:black ;
    /* position: fixed; */
  }
  .logo{
    float: left;
  }
  .navli {
    display: inline-block;
    float: right;
  }
  .navli >li {
    font-family: Montserrat, Arial, sans-serif;
    font-size: 20px;
    float: right;
    margin-right: 14px;
    list-style: none;
  }
</style>
