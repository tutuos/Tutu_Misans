# Tutu_Misans
应用于WordPress自定义字体，可加入样式css使用。
仓库地址：https://cdn.jsdelivr.net/gh/tutuos/Tutu_Misans/tutufont.你要的后缀
Misans商业可用，字体更加精美。
# 例示
@font-face {
font-family: 'tutu';
src: url('https://cdn.jsdelivr.net/gh/huiyio/Lib/fonts/AdobeCleanHanSC/AdobeCleanHanSC.eot');
src:
url('https://https://cdn.jsdelivr.net/gh/tutuos/Tutu_Misans/tutufont.eot') format('embedded-opentype'),
url('https://cdn.jsdelivr.net/gh/tutuos/Tutu_Misans/tutufont.woff2') format('woff2'),
url('https://cdn.jsdelivr.net/gh/tutuos/Tutu_Misans/tutufont.woff') format('woff'),
url('https://cdn.jsdelivr.net/gh/tutuos/Tutu_Misans/tutufont.ttf') format('truetype'),
url('https://cdn.jsdelivr.net/gh/tutuos/Tutu_Misans/tutufont.svg') format('svg');
font-weight: 400;
font-style: normal;
font-display: swap;
}
*:not([class*="icon"]):not(i) {
font-family: "tutu" !important;
}

基本上懒人操作，复制到css样式中放着就ok了。
