<template>
    <div class="foot-container">
        <div class="author">欢迎大家来到我们的二手交易平台吖</div>
    </div>
</template>

<script>
    export default {
        name: "Foot"
    }
</script>

<style scoped>
    .foot-container {
        width: 100%;
        display: flex;
        justify-content: center;
        height: 30px;
        padding-top: 10px;
        background-color: rgb(238, 229, 210);
    }

    .author {
        color: #000000;
        font-size: 16px;
    }
</style>