<template>
  <div class="Tab">
    <div class="contain">
      <div class="table-responsive">
         <b-tabs>
        <b-tab title="六合彩" active>
          <b-table striped :items="items" :fields="fields">

          </b-table>
        </b-tab>
        <b-tab title="大樂透" >
          <b-table striped :items="items" :fields="fields"></b-table>
        </b-tab>
        <b-tab title="今彩539">
          <b-table striped :items="items" :fields="fields"></b-table>
        </b-tab>
      </b-tabs>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Tab",
  props: {},
  data(){
    return{
      fields: {
        playway: {
          label: '玩法',
          variant: 'warning'
        },
        special: {
          label: '特別號'
        },
        special: {
          label: '全車'
        },
        two_star: {
          label: '二星'
        },
        three_star: {
          label: '三星'
        },
        four_star: {
          label: '四星'
        },
        five_star: {
          label: '五星'
        },
        count_two: {
          label: '天碰二'
        },
        count_three: {
          label: '天碰三'
        },
        tai: {
          label: '台號'
        }
      },
      items: [
        { playway: '單注', special: '999,999', two_star: '999,999', three_star: '999,999', four_star: '999,999', five_star: '999,999', count_two: '999,999', count_three: '999,999', tai: '999,999'},
        { playway: '單號/單碰', special: '999,999', two_star: '999,999', three_star: '999,999', four_star: '999,999', five_star: '999,999', count_two: '999,999', count_three: '999,999', tai: '999,999'},
        { playway: '成本', special: '85.8', two_star: '999,999', three_star: '74.5', four_star: '74.5', five_star: '80', count_two: '75', count_three: '45', tai: '20' },
        { playway: '賠率', special: '36', two_star: '285' ,three_star: '500', four_star: '7500', five_star: '50', count_two: '23',  count_three: '78', tai: '89'}
      ]
    }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.Tab {
  margin-bottom: 30px;
}
</style>
