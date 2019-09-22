<template>
    <div id="main">
        <Header  title="我的信息"/>
        <div id="content">
            <Login />
        </div>
        <TabBar />
    </div>
</template>
<script>
import Login from '@/components/Login'
import Header from '@/components/Header' 
import TabBar from '@/components/TabBar'
    export default {
        name:'Mine',
        components:{
            Header,
            TabBar,
            Login
        },
        data(){
            return {

            }
        }
    }
</script>
<style scoped>
    
</style>