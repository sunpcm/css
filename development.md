CSS 学习

引言

1.CSS 编码技巧

(1). 减少代码重复 用[em, rem](https://www.runoob.com/w3cnote/px-em-rem-different.html)来替换像素

a. 代码易维护 VS 代码量少

```css
border: 1px 1px 1px 0 ;
```

```css
border: 1px;
border-left-width: 0;
```

b.currentColor

c.继承

要把超链接颜色与文本一样，使用`interit`

```css
a { color: interit }
```

(2). 相信眼睛而不是数字

视觉错觉

(3). 响应式网页设计

媒体查询的断电不应该有具体的设备决定

a. 使用百分比代替固定长度，[(vw，v h, vmin, vmax)](https://www.runoob.com/cssref/css-units.html)

b.大分辨率下固定宽度，使用`max-width`

c.为替代元素(img,video,iframe)添加max-width为100%；

d.弹性盒式布局，如`display:inline-block`;

e.多列文本，指定column-width替换column-count;

(4) 合理使用简写

(5) 预处理器

