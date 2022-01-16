<template>
    <div>
        <router-link to="/table">
            <div class='test'>
                自社情報参照
            </div>
        </router-link>
        <br>
        <router-link to="/table">
            <div class='test'>
                データ公開依頼承認
            </div>
        </router-link>
    </div>
</template>

<style scoped>
    .test{
        width: 80%;
        height: 40px;
        border:1px;
        background-color: rgb(75, 132, 212);
        border-color: black;
        border-style: solid;
        border-radius: 10px;
        text-align: center;
        line-height: 40px;
        color: white;
    }

    a:link{
        color: white;
        text-decoration: none;
    }

</style>


