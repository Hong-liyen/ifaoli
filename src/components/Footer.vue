<template>
  <div class="Footer">
    <div class="contain">
      <div class="menu">
        <li><a href="">關於我們</a></li>
        <li><a href="">隱私權政策</a></li>
        <li><a href="">備用網址</a></li>
        <li><a href="">清除暫存</a></li>
      </div>
      <div class="img">
        <img src="../assets/login_icon.png" alt="">
        <img src="../assets/footer-img01.png" alt="">
        <img src="../assets/footer-img02.png" alt="">
        <img src="../assets/footer-img03.png" alt="">
      </div>
      <div class="copyright">版權所有 © 2017 Pharaoh Games copyright.</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
  props: {}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.Footer {
  padding: 10px;
  text-align: center;
  background: #202020;
  font-size: 12px;
  color: #717171;
  .menu{
    padding: 10px 0;
    li{
      font-size: 14px;
      padding: 0 15px 10px;
      a {
        color: #fff;
        text-decoration: none;

        &:hover {
            opacity: 0.6;
        }
    }

    }
  }
  .copyright{
    margin-top: 10px;
    padding: 25px 0;
    border-top: 1px solid #717171;
  }
}
</style>
