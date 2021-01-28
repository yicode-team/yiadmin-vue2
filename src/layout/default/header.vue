<template>
    <div class="layout-header">
        <div class="left">YiPack通用管理后台</div>
        <div class="center flex-center"></div>
        <div class="right"></div>
    </div>
</template>

<script>
export default {
    name: 'LayoutHeader'
};
</script>

<style lang="scss">
.layout-header {
    display: flex;
    position: absolute;
    top: 0;
    right: 0;
    left: 0;
    height: $layout-header-height;
    background-color: $layout-header-background-color;
    box-shadow: 0px 3px 6px #1f1e1e;
    z-index: 9;
    padding: 0 10px;

    .left {
        display: flex;
        align-items: center;
        font-size: 18px;
        flex: 0 0 $layout-header-height;
        padding: 5px;
        word-break: keep-all;
        white-space: nowrap;
        color: #fff;
    }
    .center {
        flex: 1 1 100%;
        font-size: 18px;
    }
    .right {
        flex: 0 0 $layout-header-height;
    }
}
</style>
