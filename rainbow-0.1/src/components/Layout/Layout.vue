<template>
    <div id="layout">
<!--            <el-header>-->
<!--               <el-container>-->
<!--                   <Navigation/>-->
<!--                   <BgVideo/>-->
<!--               </el-container>-->
<!--            </el-header>-->
<!--            <el-main>-->
<!--                <router-view/>-->
<!--            </el-main>-->
<!--            <el-footer>-->
<!--&lt;!&ndash;                <Footer/>&ndash;&gt;-->
<!--            </el-footer>-->
        <div class="header">
            <div class="container">
               <Navigation/>
               <BgVideo/>
            </div>
        </div>
    </div>
</template>

<script>

    import Navigation from "./Navigation";
    import Footer from "./Footer";
    import BgVideo from "../BgVideo/BgVideo";

    export default {
        name: "Layout",
        components: {BgVideo, Footer, Navigation}
    }
</script>

<style scoped>


    /*.el-header,*/
    /*.el-footer {*/
    /*    padding: 0;*/
    /*}*/
</style>