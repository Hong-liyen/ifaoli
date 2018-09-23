<template>
  <div class="Slick">
    <div class="contain">
      <div class="box">
        <div class="img"><img src="../assets/six_logo.png" alt="" srcset=""></div>
        <div class="time">
          <div><span>0000087</span>期<span>開獎倒數</span></div>
          <div><span>00</span>時<span>00</span>分<span>00</span>秒</div>
          <div class="icon-video-camera">觀看開獎直播</div>
        </div>
      </div>
      <div class="box">
        <div class="img"><img src="../assets/big_logo.png" alt="" srcset=""></div>
        <div class="time">
          <div><span>0000087</span>期<span>開獎倒數</span></div>
          <div><span>00</span>時<span>00</span>分<span>00</span>秒</div>
          <div class="icon-video-camera">觀看開獎直播</div>
        </div>
      </div>
      <div class="box">
        <div class="img"><img src="../assets/539_logo.png" alt="" srcset=""></div>
        <div class="time">
          <div><span>0000087</span>期<span>開獎倒數</span></div>
          <div><span>00</span>時<span>00</span>分<span>00</span>秒</div>
          <div class="icon-video-camera">觀看開獎直播</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Slick',
  props: {
    
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.Slick{
  padding: 55px 0 55px;
  color: #fff;
  text-align: center;
  >*{
    padding: 15px 0 35px;
    background-color: rgba(#717171,0.5);
    display: flex;
    justify-content: space-around;
    align-items: center;
  }
  .img{
    padding: 15px;
    height: 200px;
    font-size: 40px;
  }
  .time{
    color: #444;
    border: 2px solid  #ffcb08;
    background-color: rgba(#fff,0.5);
    padding: 15px;
    width: 300px;
    >*{
      &:before{
        font-size: 20px;
        color: #000;
      }
    }
    span{
      font-size: 18px;
      color:#bf7d16;
      font-weight: bold;
      margin: 0 5px;
    }
  }
}
</style>
