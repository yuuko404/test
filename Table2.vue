<template>
    <div class="table">
        <div class="shuju">
            <div>
                <front>事業者検索(一覧)</front>
            </div>
            <div>
                <table class="search">
                    <tr>
                        <td>社名から探す</td>
                        <td colspan="20"><input type="text"></td>
                    </tr>
                    <tr>
                        <td>事業概要から探す</td>
                        <td colspan="20"><input type="text"></td>
                    </tr>
                    <tr>
                        <td>条件から探す</td>
                        <td>業種</td>
                        <td colspan="20"><input type="text"></td>
                    </tr>
                    <tr>
                        <td></td>
                        <td>都道府県</td>
                        <td><input type="text"></td>
                        <td>市区町村</td>
                        <td><input type="text"></td>
                    </tr>
                    <tr>
                        <td></td>
                        <td>従業員数</td>
                        <td><input type="text"></td>
                        <td>〜</td>
                        <td><input type="text"></td>
                    </tr>
                    <tr>
                        <td></td>
                        <td>設立年</td>
                        <td><input type="text"></td>
                        <td>〜</td>
                        <td><input type="text"></td>
                    </tr>
                    <tr>
                        <td></td>
                        <td>売上高</td>
                        <td><input type="text"></td>
                        <td>〜</td>
                        <td><input type="text"></td>
                    </tr>
                    <tr>
                        <td></td>
                        <td>営業利益</td>
                        <td><input type="text"></td>
                        <td>〜</td>
                        <td><input type="text"></td>
                    </tr>
                    <tr>
                        <td></td>
                        <td>当期純利益</td>
                        <td><input type="text"></td>
                        <td>〜</td>
                        <td><input type="text"></td>
                    </tr>
                    <tr>
                        <td></td>
                        <td>補助金</td>
                        <td colspan="20"><input type="text"></td>
                        <td><button>検索</button></td>
                    </tr>
                </table>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: "Table2",
};
</script>

<style scoped>
.shuju {        
    text-align: center;
    padding-top: 5%;
    width: 90%;
}
front{
    font-size: 25px;
}
.search{
    width:100%;
    height: 100%;
    font-size: 20px;
    text-align: left;
    border-spacing: 20px 15px;
}
input {
    width:100%;
    height: 20px;
}
tr
{
    height:30px;
}
</style>