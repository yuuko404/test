<template>
    <div class="wrapper">
        <div class="header">
        <Header/>
        </div>
        <Top/>
        <div class='main'>
            <div class='left'>
                <Lefter/>
            </div>
            <div class='right'>
                <router-view/>
            </div>
        </div>
        <div class='bottom'>
        </div>
        <div class='footer'>
            <Footer/>
        </div>
    </div>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import Lefter from './views/Lefter.vue'
import Top from './components/Top.vue'

export default {
    name:'App',
    components:{Header,Footer, Lefter, Top}
}
</script>

<style>
    html,body{
        width: 100%;
        height: 100%;
    }

    #app{
       position: absolute;
       top: 0;
       right: 0;
       bottom: 0;
       left: 0; 
    }

    *{
        margin:auto;
        padding: 0px;
    }

    .wrapper{
        display: flex;
        flex-direction: column;
        min-height: 100%;
        width: 100%;
    }

    .header{
        width: 100%;
        flex: 0;
        background-color: blue;
    }

    .main{
        flex: 1;
        position: relative;
        background-color: white;
        width: 100%;
    }

    .footer{
        width: 100%;
        flex: 0;
        background-color: red;
    }

    .bottom{
        display: block;
        width: 100%;
        padding-top: 1px;
        background-color: white;
    }

    .left{
        position: absolute;
        margin-left: 0px;
        width: 20%;
        height: 100%;
        background-color: white;
    }
    .right{
        height: 99%;
        width: 80%;
        position: absolute;
        margin-left: 20%;
        background-color: rgb(241, 248, 239);
    }
</style>