<template>
  <div class="memberContainer">
    <div class="login">
      <div class="left">
        <span class="glyphicon glyphicon-user" aria-hidden="true"></span>
      </div>

      <button type="button" class="mui-btn mui-btn-danger mui-btn-outlined">立即登录</button>
    </div>

    <div class="mui-card">
      <div class="mui-card-header">
        <span class="myOrder">我的订单</span>
        <span class="AllOrder">查看全部订单  ></span>
      </div>
      <div class="mui-card-content">
        <div class="mui-card-content-inner">
          <div class="orderPay">
            <span class="mui-icon-extra mui-icon-extra-card"></span>
            <span>待付款</span>
          </div>
          <div class="OrderGoods">
            <span class="mui-icon mui-icon-upload"></span>
            <span>待发货</span>
          </div>
          <div class="express">
            <span class="mui-icon-extra mui-icon-extra-express"></span>
            <span>待收货</span>
          </div>
          <div class="comment">
            <span class="mui-icon-extra mui-icon-extra-comment"></span>
            <span>评价</span>
          </div>
          <div class="custom">
            <span class="mui-icon-extra mui-icon-extra-custom"></span>
            <span>退款/售后</span>
          </div>
        </div>
      </div>
      <div class="mui-card-footer">
        <div class="logistics">
          <span>最新物流</span>
          
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.memberContainer {
  .login {
    padding-top: 30px;
    display: flex;
    align-content: flex-start;
    .left {
      margin-left: 20px;
      width: 60px;
      height: 60px;
      background-color: #eee;
      border: 1px solid #ccc;
      border-radius: 50%;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    span {
      font-size: 25px;
      color: #aaa;
    }
    .mui-btn-outlined {
      margin-top: 10px;
      border-radius: 20px;
      margin-left: 25px;
      height: 40px;
      width: 120px;
    }
  }
  .mui-card {
    .mui-card-header {
      .myOrder{
        font-size: 18px;
      }
      .AllOrder {
        font-size: 12px;
        color: #aaa;
      }
    }
    .mui-card-content {
      .mui-card-content-inner {
        display: flex;
        align-content: center;
        justify-content: space-around;
      }
      .mui-icon-extra{
        color:orangered;
        font-size: 35px;
      }
      .mui-icon{
        font-size: 35px;
        color:orangered;

      }
      .OrderGoods {
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 50px;
        height: 40px;
        span {
          text-align: center;
          display: block;
        }
      }
      .orderPay {
        width: 50px;
        height: 40px;
        span {
          text-align: center;
          display: block;
        }
      }
      .express {
        width: 50px;
        height: 40px;
        span {
          text-align: center;
          display: block;
        }
      }
      .comment {
        width: 50px;
        height: 40px;
        transform: translateY(8px);
        .mui-icon-extra-comment{
          font-size: 27px;
          
        }
        span {
          text-align: center;
          display: block;
        }
      }
      .custom {
        width: 60px;
        height: 40px;
        span {
          text-align: center;
          display: block;
        }
      }
    }
    .mui-card-footer{
      .logistics{
        display:flex;
        
       justify-content: flex-end;
      }
    }
  }
}
</style>