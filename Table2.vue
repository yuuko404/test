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
                        <td colspan="20">
                            <select>
                                <option value="0">プルダウル</option>
                                <option value="1">test1</option>
                                <option value="2">test2</option>
                            </select>   
                        </td>
                    </tr>
                    <tr>
                        <td></td>
                        <td>都道府県</td>
                        <td>
                            <select>
                                <option value="0">プルダウル</option>
                                <option value="1">test1</option>
                                <option value="2">test2</option>
                            </select>   
                        </td>
                        <td>市区町村</td>
                        <td>
                            <select>
                                <option value="0">プルダウル</option>
                                <option value="1">test1</option>
                                <option value="2">test2</option>
                            </select> 
                        </td>
                    </tr>
                    <tr>
                        <td></td>
                        <td>従業員数</td>
                        <td>
                            <select>
                                <option value="0">プルダウル</option>
                                <option value="1">test1</option>
                                <option value="2">test2</option>
                            </select> 
                        </td>
                        <td>〜</td>
                        <td>
                            <select>
                                <option value="0">プルダウル</option>
                                <option value="1">test1</option>
                                <option value="2">test2</option>
                            </select> 
                        </td>
                    </tr>
                    <tr>
                        <td></td>
                        <td>設立年</td>
                        <td>                    
                            <select>
                                <option value="0">プルダウル</option>
                                <option value="1">test1</option>
                                <option value="2">test2</option>
                            </select> 
                        </td>
                        <td>〜</td>
                        <td>
                            <select>
                                <option value="0">プルダウル</option>
                                <option value="1">test1</option>
                                <option value="2">test2</option>
                            </select> 
                        </td>
                    </tr>
                    <tr>
                        <td></td>
                        <td>売上高</td>
                        <td>                   
                            <select>
                                <option value="0">プルダウル</option>
                                <option value="1">test1</option>
                                <option value="2">test2</option>
                            </select> 
                        </td>
                        <td>〜</td>
                        <td>
                            <select>
                                <option value="0">プルダウル</option>
                                <option value="1">test1</option>
                                <option value="2">test2</option>
                            </select> 
                        </td>
                    </tr>
                    <tr>
                        <td></td>
                        <td>営業利益</td>
                        <td>                       
                            <select>
                                <option value="0">プルダウル</option>
                                <option value="1">test1</option>
                                <option value="2">test2</option>
                            </select>
                        </td>
                        <td>〜</td>
                        <td>                            
                            <select>
                                <option value="0">プルダウル</option>
                                <option value="1">test1</option>
                                <option value="2">test2</option>
                            </select>
                        </td>
                    </tr>
                    <tr>
                        <td></td>
                        <td>当期純利益</td>
                        <td>
                            <select>
                                <option value="0">プルダウル</option>
                                <option value="1">test1</option>
                                <option value="2">test2</option>
                            </select>   
                        </td>
                        <td>〜</td>
                        <td>
                            <select>
                                <option value="0">プルダウル</option>
                                <option value="1">test1</option>
                                <option value="2">test2</option>
                            </select> 
                        </td>
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
.table{
    overflow-y: scroll;
    overflow-x: hidden;
    height: 100%;
}
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
select{
    text-align: center;
    width:160px;
    height: 25px;
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