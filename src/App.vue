<template>
    <div id="app">
        <router-view />
    </div>
</template>

<script>
export default {
    name: "App",
};
</script>
<style>
/* 自定义滚动条样式 */
@charset "utf-8";
::-webkit-scrollbar {
    width: 6px;
}

/*定义滚动条轨道 内阴影+圆角*/
::-webkit-scrollbar-track {
    border-radius: 2px;
}

/*定义滑块 内阴影+圆角*/
::-webkit-scrollbar-thumb {
    border-radius: 2px;
    -webkit-box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
}
@font-face {
  font-family: 'webfont';
  font-display: swap;
  src: url('//at.alicdn.com/t/webfont_z6y0wsihrc.eot'); /* IE9*/
  src: url('//at.alicdn.com/t/webfont_z6y0wsihrc.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */
  url('//at.alicdn.com/t/webfont_z6y0wsihrc.woff2') format('woff2'),
  url('//at.alicdn.com/t/webfont_z6y0wsihrc.woff') format('woff'), /* chrome、firefox */
  url('//at.alicdn.com/t/webfont_z6y0wsihrc.ttf') format('truetype'), /* chrome、firefox、opera、Safari, Android, iOS 4.2+*/
  url('//at.alicdn.com/t/webfont_z6y0wsihrc.svg#Alibaba-PuHuiTi-Regular') format('svg'); /* iOS 4.1- */
}
.web-font{
    font-family:"webfont" !important;
    font-size:16px;font-style:normal;
    -webkit-font-smoothing: antialiased;
    -webkit-text-stroke-width: 0.2px;
    -moz-osx-font-smoothing: grayscale;
}
</style>
