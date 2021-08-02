# 这是我的第一篇博客

## 内容：

* HTML是谁发明的？
   答：李爵士

* HTML起手应该写什么？
   答：HTML应该先打开VScode，写 "!"，再按下Tab键；
   其次再写一个清除默认样式的css，例：
``` css
    a {
   color: inherit;
   text-decoration: none;
      }

     ol,ul {
    list-style: none;
   }
```
   最后写一些标签，例如div,main,ul>li,a,style(样式在style里写)

``` html
<style>
    .bordered{
        border: 10px solid red;
    }
</style>
<div class="bordered"> </div>
```

* 常用的表章节的标签有哪些，分别是什么意思?
   答：h1-h6 表示标题，h1是字体最大的标题，往后字体越来越小；
       section 表示章节；
       article 表示一篇文章；
       main 表示主函数；
       aside 表示侧边的，次要的；
       p 表示段落。
* 全局属性有哪些？
   答：contenteditable 表示规定元素内容是否可编辑
       class 表示规定元素的一个或多个类名
       hidden 表示隐藏
       id 表示元素的唯一id
       title 表示元素的额外信息
       style 表示元素的行内CSS样式
       tabindex 表示元素tab键的次序
* 常用的内容标签有哪些，分别是什么意思？
   答：ol+li 表示有序的列表
       ul+li 表示无序的列表
       dl+dt+dd 表示表格标签或者组合标签
       pre 表示将排版格式原封不动地展示出来
       code 表示内容都是等宽的
       hr 表示分割线
       br 表示换行
       a 表示超链接
       em 表示强调文本，一般显示为斜体
       strong 表示语义更强地强调文本，一般显示粗体
       quote 表示引用（行内）
       blockquote 表示块引用，会换行