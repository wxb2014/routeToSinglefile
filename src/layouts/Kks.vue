<template>
 <div class='tc_user font'>
  <top></top>
  <middle></middle>
  <bottom></bottom>
  </div>
</template>

<script>  

  import Top from '../components/Top.vue'
  import Middle from '../components/Middle.vue'
  import Bottom from '../components/Bottom.vue'

  export default {
    components: {
      Top,
      Middle,
      Bottom
    }
  }
</script>

<style scoped>
  .tc_user {
            width: 100%;
            display: block;
            overflow: hidden;
            line-height: 40px;
            padding: 5px 0 15px 0;
        }

  .tc_user font {
      width: 33.33%;
      background: #eee;
      display: block;
      overflow: hidden;
      float: left;
      text-align: center;
      font-size: 14px;
      cursor: pointer;
  }

  .tc_user font.tive {
      background: #ff8000;
      color: #fff;
  }

  .verify {
      width: 150px;
      height: 42px;
      float: right
  }
</style>
