#demo2

##连接demo

###内嵌式链接

* 外部链接
[百度](https://baidu.com)  

* 内部链接1  链接仓库的其他文件
[demo1](demo1.md)  

* 内部链接2  链接本文档的其他部分
[代码块demo](demo2.md/代码块-demo)

###引用式链接

* 外部链接  
[百度]  
[百度](baidu)  

* 内部链接  
[demo1]  
[代码块demo]


##图片demo
###图片的内嵌式链接
* 外部图片  
![图片名称](地址 "鼠标放上显示内容")  
![baidu]( https://www.baidu.com/img/flexible/logo/pc/result.png  "百度logo")  

* 内部图片
![baidu](images/baidu.png 怎么不出来啊)

###图片的引用式链接
* 外部图片  
![baidu ][baidu logo]

* 内部图片  
![baidu ][baidu.png]

##引用demo

>这是一个引文

  ————出自《不知道女士》  

>>应该是双重引文吧      
  

>>>这是三重引文,好像微博评论转发,呃软件又出现问题了么


##代码块demo

* 行内代码
这个代码是用来声明变量是`var a=10`,打印变量内容是`console.log`调用

* 块式代码

```javascript
var a=10
console.log(a)
```

    var a=10
    console.log(a)


<!--下面是文档中用到的链接-->
[百度]:https://www.baidu.com
[baidu]:https://www.baidu.com
[demo1]:demo1.md
[代码块demo]:demo2.md/代码块-demo
[baidu logo]:https://www.baidu.com/img/flexible/logo/pc/result.png
[baidu.png]:images/baidu.png
