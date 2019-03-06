<template>
    <div class="container">
        <div class="content">

        </div>
        <div class="footer">
            <div class="button">
                <el-button>推荐</el-button>
            </div>
            <div class="button">
                <el-button>兴趣</el-button>
            </div>
            <div class="button">
                <el-button>日志</el-button>
            </div>
            <div class="button">
                <el-button>简历</el-button>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .container{
        width: 7.5rem;
        display: flex;
        flex-direction: column;
    }
    .content{
        width: 7.5rem;
        flex: 1;
        background-color: green;
    }
    .footer{
        width: 100%;
        height: 50px;
        background-color: #c2c2c2;
        position: fixed;
        bottom: 0;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }
    .button{
        width: 25%;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }
</style>
