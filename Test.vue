<template>
<div>
        <!-- classはスタイル適用のため -->
        <v-data-table
          :headers="headers"
          :items="items"
          class="resizable-column"
          hide-default-footer
          :expanded.sync="expanded"
          show-expand
        >
        <template v-slot:expanded-item="{ headers, item }">
            <td :colspan="headers.length">
                {{item}}
            </td>
      </template>
        </v-data-table>
 <v-simple-table class="resizable-column2">
      <template v-slot:default>
        <thead>
          <tr>
            <td class="text-center">&nbsp;&nbsp;sss</td>
            <td class="text-center">&nbsp;&nbsp;sss</td>
            <td class="text-center">&nbsp;&nbsp;sss</td>
          </tr>
        </thead>
        <tbody>
         <tr>
             <td>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;test
             </td>
                          <td>
                &nbsp;&nbsp;&nbsp;test
             </td>
                          <td>
                &nbsp;&nbsp;&nbsp;test
             </td>
         </tr>
        </tbody>
      </template>
    </v-simple-table>
</div>
</template>

<script>
import Table from './Table.vue'
export default {
  components: { Table },
  data() {
    return {
      headers: [
        { text: "行1", value: "col1", align: "center" },
        { text: "行2", value: "col2", align: "center" },
        { text: "行3", value: "col3", align: "center" },
      ],
      items: [
          { col1: "hoge", col2: "fuga", col3: "foo" }
          ],
    }
  },
  /* ここに色々追記していく */
}
</script>

<style scoped>
/* ヘッダに縦線出すよ */
.resizable-column /deep/ th + th + th {
  border-left: 1px solid grey;
}

.resizable-column2 /deep/ th + th +th{
  border-left: 1px solid grey;
}

.resizable-column /deep/ th {
  background-color: blue;
}
.resizable-column /deep/ td + td + td{
  border-left: 1px solid grey;
}
td{
    text-align: center;
    border: 1px solid grey;
}
</style>