# 颜色和透明度

css中颜色的表示方式
1. rgb(0-255,0-255,0-255)
2. #00000   十六进制颜色
3. 关键词  red  green 
4. rgba(0,0,0,.5)
   可以让文字颜色、背景颜色、变成透明


background:transparent
opacity：0 -1;表示透明度 
filter：Alpha(opacity=0-100); 滤镜

浏览器前缀

火狐的前缀	-moz-
IE			-ms-
chrome		-webkit-
欧朋		-o-

模糊效果：
-webkit-filter:blur(10px);

- 灰度效果
-webkit-filter:grayscale(0 | 1);
1 灰色
0 彩色

