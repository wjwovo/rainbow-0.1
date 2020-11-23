<template>
    <video autoplay="" loop="" muted="" width="100%">
        <source src="//mi.xiguacity.cn/videos/IndexVideoS-2d03e80e910814c640e3f96ff1dac1f4.mp4" type="video/mp4">
    </video>
</template>

<script>
    export default {
        name: "BgVideo"
    }
</script>

<style scoped>
    video{
        position: absolute;
        top: 0;
        z-index: -1
    }
</style>