<template>
  <div class="Tab">
    <div class="contain">
      <div class="table-responsive">
         <b-tabs>
        <b-tab title="六合彩" active>
          <b-table :items="items" :fields="fields">

          </b-table>
        </b-tab>
        <b-tab title="大樂透" >
          <b-table :items="items" :fields="fields"></b-table>
        </b-tab>
        <b-tab title="今彩539">
          <b-table :items="items" :fields="fields"></b-table>
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
        all_car: {
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
        },
        nail_three: {
          label: '特尾三'
        },
        color_ball: {
          label: '組合/球色'
        },
        zodiac: {
          label: '生肖投注'
        }
      },
      items: [
        { playway: '單注', special: '999,999', all_car:'999,999', two_star: '999,999', three_star: '999,999', four_star: '999,999', five_star: '999,999', count_two: '999,999', count_three: '999,999', tai: '999,999', nail_three: '999,999', color_ball: '999,999', zodiac:'999,999'},
        { playway: '單號/單碰', special: '999,999', all_car:'999,999', two_star: '999,999', three_star: '999,999', four_star: '999,999', five_star: '999,999', count_two: '999,999', count_three: '999,999', tai: '999,999', nail_three: '999,999', color_ball: '999,999', zodiac:'999,999'},
        { playway: '成本', special: '85.8', all_car:'999,999', two_star: '999,999', three_star: '74.5', four_star: '74.5', five_star: '80', count_two: '75', count_three: '45', tai: '20', nail_three: '65', color_ball: '75',zodiac:'98' },
        { playway: '賠率', special: '36', all_car:'999,999', two_star: '285' ,three_star: '500', four_star: '7500', five_star: '50', count_two: '23',  count_three: '78', tai: '89', nail_three: '20', color_ball: '45',zodiac:'85'}
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
