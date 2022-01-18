<template>
    <div class="main">
        <div class="title">test</div>
        <div class="conect">
            <p>acout</p>
            <input style="text">
            <p>password</p>
            <input style="text">
        </div>
        <div class='word'>
            注意事項
            <ul>
                <li>テキスト</li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
  name: "Login",
};
</script>

<style scoped>
.main {
  width: 100%;
  height: 100%;
  padding-top: 30px;
  margin: 0px auto;
  text-align: center;
}

.title{
    width: 300px;
    font-size: 50px;
    font-weight: bold;
}

.conect{
    width: 300px;
    text-align: left;
    font-size: 25px;
}

input{
    width: 100%;
    height: 30px;
}

.word{
    width: 300px;
    padding-left: 0;
    padding-top: 30px;
    text-align: left;
}
</style>