# iframe元素

通常用于在页面中嵌入另一个页面

iframe 可替换元素

1. 通常是行盒

2. 通常显示的内容取决于元素的属性

3. CSS不能完全控制其中的样式

4. 具有行块盒的特点，宽度和高度可以设置

iframe和target的用法
```HTML
<body>
    <a href="https://www.baidu.com" target="_blank">百度</a>
    <a href="https://douyu.com" target="myframe">斗鱼</a>
    <a href="https://www.taobao.com" target="myframe">淘宝</a>

    <iframe src="https://player.bilibili.com/player.html?aid=212421219&bvid=BV13a411t74Y&cid=553599539&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

    <iframe name="myframe" src="https://www.taobao.com" frameborder="3"></iframe>
</body>
```