## 网站性能优化项目

你要做的是尽可能优化这个在线项目的速度。

### 目标

    1.index.html 在移动设备和桌面上的 PageSpeed 分数至少为90分。
    2.对 views/js/main.js 进行的优化可使 views/pizza.html 在滚动时保持 60fps 的帧速。
    3.用 views/pizza.html 页面上的 pizza 尺寸滑块调整 pizza 大小的时间小于5毫秒。

### 优化概述

#### index.html
    1.异步加载谷歌字体
    2.css内联
    3.js脚本加上async，异步加载
    4.使用pagespeed中提供的优化后的图片以及压缩后的js文件（之前也用过gulp来压缩图片和文件，结果pagespeed还是提示图片压缩的不够，所以就直接用pagespeed里面提供的图片和文件了）

#### pizza.html
