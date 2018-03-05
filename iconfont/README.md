# Iconfont库-自定义版

[TOC]

----


图标来自 [iconfont 阿里巴巴矢量图标库](http://www.iconfont.cn/?spm=a313x.7781069.1998910419.d4d0a486a)

## Symbol Icon(推荐) 

[查看文档链接](https://liuqing650.github.io/view/iconfont/demo_symbol.html)



![](https://liuqing650.github.io/view/iconfont/symbol.png)


使用教程

```
// 全局引用
<script src="iconfont.js"></script>

// 使用
<Icon type={'icon-wxbbaobiao'} size="sm" />
```



global.less

```
.am-icon {
    /* 通过设置 font-size 来改变图标大小 */
    width: 1em; height: 1em;
    /* 图标和文字相邻时，垂直对齐 */
    vertical-align: -0.15em;
    /* 通过设置 color 来改变 SVG 的颜色/fill */
    fill: currentColor;
    /* path 和 stroke 溢出 viewBox 部分在 IE 下会显示
       normalize.css 中也包含这行 */
    overflow: hidden;
}

```


##  Fontclass Icon

[查看文档链接](https://liuqing650.github.io/view/iconfont/demo_fontclass.html)



![](https://liuqing650.github.io/view/iconfont/fontclass.png)



## Unicode Icon

[查看文档链接](https://liuqing650.github.io/view/iconfont/demo_unicode.html) 



![](https://liuqing650.github.io/view/iconfont/unicode.png)
