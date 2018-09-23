<template>
  <div class="Header">
    <div class="contain">
      <img alt="Vue logo" src="../assets/logo.png">
      <div class="menu">
        <li class="icon-dice"><a href="#">六合彩</a></li>
        <li class="icon-ball"><a href="#">大樂透</a></li>
        <li class="icon-spades"><a href="#">今彩539</a></li>
      </div>
      <div class="member">
        <span class="icon-user">Andy</span>
        <span class="icon-coin-yen">100,0000</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.Header{
  padding: 0.4em 0;
  background-color: rgba($color: #000000, $alpha: 0.8);
  color: #fff;
  font-size: 18px;
  border-bottom:1px solid #c79c18;
  >*{
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .menu{
    li{
      padding: 0 20px;
      a {
        color: #fff;
        text-decoration: none;

        &:hover {
            opacity: 0.6;
        }
    }
    }
  }
  span{
    margin-right: 10px;
  }
}
</style>
