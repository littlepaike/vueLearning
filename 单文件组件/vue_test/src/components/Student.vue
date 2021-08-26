<template>
    <div>
        <!-- 组建的结构 -->
        <div class="demo">
            <h2>学生名称：{{name}}</h2>
            <h2>学生年龄：{{age}}</h2>
        </div>
    </div>
</template>


<script>
// 组件交互相关代码
export default{
    name:'Student',
    data(){
        return{
            name:'paike',
            age:18
        }
    },
}

</script>
