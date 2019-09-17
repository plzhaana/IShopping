<template>
  <div class="recommend">
    
      <a href="#">
        <img src="~assets/img/recommend/1.png" alt="">
        <span>十点抢券</span>
      </a>
      <a href="#">
        <img src="~assets/img/recommend/2.png" alt="">
        <span>好物特卖</span>
      </a>
      <a href="#">
        <img src="~assets/img/recommend/3.png" alt="">
        <span>内购福利</span>
      </a>
      <a href="#">
        <img src="~assets/img/recommend/4.png" alt="">
        <span>初秋上心</span>
      </a>
    
  </div>
</template>

<script>
  export default {
    name: "RecommendView"
    // props: {
    //   recommends: {
    //     type: Array,
    //     required: true
    //   }
    // }
  }
</script>

<style scoped>
  .recommend {
    display: flex;
    margin-top: 10px;
    font-size: 14px;
    padding-bottom: 30px;
    border-bottom: 10px solid #eee;
  }

  .recommend a  {
    flex: 1;
    text-align: center;
  }

 
  .recommend img {
    width: 80px;
    height: 80px;
    margin-bottom: 10px;
  }

 
</style>