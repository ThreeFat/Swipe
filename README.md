# Swipe
> 一款原生的专用于移动端导航类组件触摸滑动的小插件
> Swipe的使用非常简单,它只有一个功能,那就是帮助我们在制作移动端页面时,导航条类组件的触摸滑动添缓冲效果,而且它非常的小

## Swipe 使用方法
- 引包

`<script src="./lib/swipe.js"></script>`

- API 
```
Swipe.iScroll({
        // 获取需要添加方法的元素
        swipeDom:document.querySelector(".nav"),
        // 定义滑动的方向
        swipeType:'x',
        // 缓动的距离
        swipeDistance: 0
    });
```
