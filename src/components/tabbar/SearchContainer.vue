<template>
  <div class="searchContainer">
    <div class="mui-input-row mui-search">
      <input type="search" class="mui-input-clear" placeholder />
    </div>
    <div class="search">
      
        <ul>
        <li><a href="javascript:;">水果</a></li>
        <li><a href="javascript:;">鞋包</a></li>
        <li><a href="javascript:;">百货</a></li>
        <li><a href="javascript:;">家纺</a></li>
        <li><a href="javascript:;">女装</a></li>
        <li><a href="javascript:;">食品</a></li>
        <li><a href="javascript:;">手机</a></li>
        <li><a href="javascript:;">内衣</a></li>
        <li><a href="javascript:;">男装</a></li>
        <li><a href="javascript:;">母婴</a></li>
        <li><a href="javascript:;">运动</a></li>
        <li><a href="javascript:;">健康</a></li>
        <li><a href="javascript:;">充值</a></li>
        <li><a href="javascript:;">海淘</a></li>
        </ul>
      
      <div class="info"></div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.searchContainer {
  // height: 100%;
  .mui-input-clear {
    margin-bottom: 5px;
  }
  .search {
    border-top: 1px solid #ccc;
    // height: 100%;
    display: flex;
    min-height: 100vh;
    ul {
      flex: 1;
      // background-color: aqua;
      // display: flex;
      // flex-direction: row;
      list-style: none;
      padding-left: 5px;
      a{
        color: black;
        text-decoration: none;
        border-bottom: 1px solid #ccc;
        display: block;
        height: 45px;
        text-align: center;
        line-height: 45px;
        font-size: 18px;
      }
    }
    .info {
      flex: 4;
      background-color: cadetblue;

      // height: 100%;
    }
  }
}
</style>