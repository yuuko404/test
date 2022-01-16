<template>
    <div id='header'>
        <div id='title'>test</div>
        <div id='commpany'>
            ID:00000000
            <br>
            アカウント:ABC株式会社
        </div>
        <div id='login'>
            <button>login</button>
        </div>
    </div>
</template>

<style scoped>
    #header{
        position:relative;
        width: 100%;
        height: 80px;
        background-color: rgb(64, 117, 192);
    }

    #title{
        font-size: 50px;
        color:white;
        text-align: center;
        line-height: 80px;
    }

    #commpany{
        position: absolute;
        top:10px;
        right: 80px;
        font-size: 10px;
        color: white;
    }

    #login{
        position: absolute;
        top:15px;
        right: 20px;
    }
</style>