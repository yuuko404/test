<template>
    <div class="table">
        <div class="shuju">
            <front>▲自社概要情報</front>
            <table class="scroll">
                <thead>
                <tr>
                    <th></th>
                    <th colspan="5">項目名</th>
                    <th colspan="6">値</th>
                </tr>
                </thead>
                <tbody>
                <tr>
                    <td class='blue'>1</td>
                    <td colspan="3">事業者基本情報</td>
                    <td colspan="2">事業者名</td>
                    <td　colspan="6">サンプル会社</td>
                </tr>
                <tr>
                    <td class='blue'>２</td>
                    <td colspan="3"></td>
                    <td colspan="2">所在地</td>
                    <td　colspan="6">東京都江東区豊洲</td>
                </tr>
                <tr>
                    <td class='blue'>3</td>
                    <td colspan="3"></td>
                    <td colspan="2">電話番号</td>
                    <td　colspan="6">0000-00-0000</td>
                </tr>
                <tr>
                    <td class='blue'></td>
                    <td colspan="3"></td>
                    <td colspan="2"></td>
                    <td　colspan="6"></td>
                </tr>
                <tr>
                    <td class='blue'></td>
                    <td colspan="3"></td>
                    <td colspan="2"></td>
                    <td　colspan="6"></td>
                </tr>
                <tr>
                    <td class='blue'></td>
                    <td colspan="3"></td>
                    <td colspan="2"></td>
                    <td　colspan="6"></td>
                </tr>
                </tbody>
            </table>
            <br />
            <br />
            <br />
            <front>▲自社申請履歴情報</front>
            <table class="scroll">
                <thead>
                    <tr>
                        <th></th>
                        <th colspan="4">制度</th>
                        <th colspan="2">システム</th>
                        <th colspan="4">登録日</th>
                        <th colspan="2">参照</th>
                    </tr>
                </thead>
                <tbody>
                <tr>
                    <td class='blue'>1</td>
                    <td colspan="4">JAPANプランド</td>
                    <td colspan="2">jGrants</td>
                    <td　colspan="4">2021/01/11</td>
                    <td　colspan="2"><button><router-link to='/test2'>詳細</router-link></button></td>
                </tr>
                <tr>
                    <td class='blue'>2</td>
                    <td colspan="4">〇〇制度</td>
                    <td colspan="2">〇〇システム</td>
                    <td　colspan="4">2021/01/23</td>
                    <td　colspan="2"><button><router-link to='/test2'>詳細</router-link></button></td>
                </tr>
                <tr>
                    <td class='blue'>3</td>
                    <td colspan="4">〇〇制度</td>
                    <td colspan="2">〇〇システム</td>
                    <td　colspan="4">2021/01/10</td>
                    <td　colspan="2"><button><router-link to='/test2'>詳細</router-link></button></td>
                </tr>
                <tr>
                    <td class='blue'></td>
                    <td colspan="4"></td>
                    <td colspan="2"></td>
                    <td　colspan="4"></td>
                    <td　colspan="2"></td>
                </tr>
                <tr>
                    <td class='blue'></td>
                    <td colspan="4"></td>
                    <td colspan="2"></td>
                    <td　colspan="4"></td>
                    <td　colspan="2"></td>
                </tr>
                </tbody>
            </table>
        </div>
    </div>
</template>

<script>
export default {
  name: "Table",
};
</script>

<style scoped>
.shuju {
    padding-top: 5%;
    width: 90%;
    vertical-align: middle;
}
table {
  border-spacing: 0px;
  border-collapse: collapse;
}

table th,
table td {
  height: 60px;
  text-align: center;
  border: 1px solid white;
}

table thead {
  color: white;
  background-color: rgb(75, 132, 212);
}

table tbody {
    display: block;
    width: calc(100%+8px);
    height: 200px;
    overflow-y: auto;
    background-color:rgb(207, 221, 241);
}

table thead tr,
table tbody tr {
    box-sizing: border-box;
    table-layout: fixed;
    display: table;
    width: 100%;
}

.blue{
    background-color: rgb(75, 132, 212);
}

a:link{
    color: white;
    text-decoration: none;
}
</style>