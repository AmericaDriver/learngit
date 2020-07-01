## 链接

***链接使用方法：***

> [链接名称]（链接地址）
>
> <链接地址>

	这是一个链接[双击是傻瓜](http://baidu.com)

显示效果如下：

这是一个链接[双击是傻瓜](https://www.baidu.com)

> 直接使用链接地址

    <https://www.baidu.com>

显示效果如下:

<https://www.baidu.com>

### 高级链接

我们可以通过变量来设置一个链接，变量赋值在文档末尾进行:

	这个链接用1作为网址变量 [GOOgle][1]
	这个链接用study作为网址变量[Study][study]
	然后在文档的结尾为变量赋值(网址)
	
		[1]：http://www.google.com/
		[study]: http://www.study.com/

显示效果如下:

[Google][1]

[Study][study]

[ 1 ]: http://www.google.com/
[study]: http://www.study.com

---

[![](https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=1555620250,991762746&fm=26&gp=0.jpg)](https://www.baidu.com)
123

[![](https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=1555620250,991762746&fm=26&gp=0.jpg "test")](https:www.baidu.com "markdown")
2122112

> Follow your heart.

---

[锚点链接][anchor-id]

[anchor-id]: https://www.mdeditor.com/
[mailto:test.test@gmail.com](mailto:test.test@gmail.com)
GFM a-tail link @pandao
邮箱地址自动链接 test.test@gmail.com  www@vip.qq.com

> @pandao