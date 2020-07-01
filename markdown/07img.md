### markdown图片格式语法

	![alt 属性文本](图片地址)
	![alt 属性文本](图片地址 "可选标题")

+ 开头一个感叹号
+ 接着一个方括号，里面放上图片的替代文字
+ 接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上选择性的'title'属性的文字

__实例__:

```
![迪丽热巴](http://img0.imgtn.bdimg.com/it/u=186050584,3291659276&fm=26&gp=0.jpg)
![高圆圆](https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=3452534833,4192399921&fm=26&gp=0.jpg)
```

![迪丽热巴](https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=1555620250,991762746&fm=26&gp=0.jpg "未婚")

![高圆圆](https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=3452534833,4192399921&fm=26&gp=0.jpg "已婚")

---

当然你也可以像网址那样对图片网址使用变量:

```
这个链接用1作为网址变量[LOL][1]
然后在文档的结尾为变量赋值(网址)
[1]:https://lol.qq.com/
```

显示效果:

这个链接用1作为网址变量[LOL][1]

[1]:https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=3452534833,4192399921&amp;fm=26&amp;gp=0.jpg

