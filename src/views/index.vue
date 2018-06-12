<style lang="less">
    .layout {
        width: 100%;
        height: 100%;
        /*border: 1px solid red;*/
        overflow: hidden;
        .layout-header-center {
            position: absolute;
            width: 100%;
            background-color: #cccccc !important;
        }
        .ivu-layout-header {
            padding: 0 50px;
            height: 48px;
            line-height: 48px;
            border-bottom: 4px solid #00a2e8;
        }
        .layout-footer-center {
            position: fixed;
            bottom: 0;
            width: 100%;
            background-color: #2c4060 ;
        }
        .ivu-layout-footer {
            padding: 2px 50px;
            color: #495060;
            font-size: 14px;
        }
        .layout-content-center {
            position: absolute;
            width:100%;
            top: 53px;
            left: 0;
            bottom: 29px;
            background-color: #ccc !important;
        }
    }


</style>
<template>
    <div class="layout">
        <Header class="layout-header-center">Header</Header>
        <Layout class="layout-content-center">
            <Sider hide-trigger collapsible>Sider</Sider>
            <Content>Content</Content>
        </Layout>
        <Footer class='layout-footer-center'>Footer</Footer>
    </div>
</template>
<script>
    export default {}
</script>
