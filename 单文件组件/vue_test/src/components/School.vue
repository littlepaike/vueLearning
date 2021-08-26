<template>
    <div>
        <!-- 组建的结构 -->
        <div class="demo">
            <h2>学校名称：{{schoolName}}</h2>
            <h2>学校地址：{{address}}</h2>
            <button @click="showName">点我提示学校名称</button>
        </div>
    </div>
</template>


<script>
// 组件交互相关代码
export default{
    name:'School',
    data(){
        return{
            schoolName:'aidpaike',
            address:'beijing'
        }
    },
    methods: {
        showName(){
            alert(this.schoolName)
        }
    },
}

</script>

<style>
    .demo{
        background-color: orange;
    }
</style>