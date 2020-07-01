### apache2.4 配置虚拟主机

在apache的httpd.conf 中加入如下2行代码:

```html
#启用虚拟主机 添加相应的扩展
LoadModule vhost_alias_module modules/mod_vhost_alias.so
#引入虚拟机配置文件
Include conf/vhosts/*.conf
```

在`conf\vhosts`中添加对应虚拟主机文件:

```
www.test1.conf
www.test2.conf
```

具体配置:

```
<VirtualHost *:80>
    ##配置网站根目录
    DocumentRoot "D:/WWW/study/"
    ##配置网站域名
    ServerName www.test.com
    FcgidInitialEnv PHPRC "D:/phpstudy_pro/Extensions/php/php7.3.4nts"
    AddHandler fcgid-script .php
    FcgidWrapper "D:/phpstudy_pro/Extensions/php/php7.3.4nts/php-cgi.exe" .php
</VirtualHost>
<Directory "D:/WWW/study/">
      ##indexes如果根目录下没有index文件则展示整个目录的文件路径，去掉indexes如果没有index会报错
      Options Indexes FollowSymLinks ExecCGI
      AllowOverride All
      ##先前查allow 再检查deny
      Order allow,deny
      Allow from all
      Require all granted
      ## indexes
	  DirectoryIndex index.php index.html error/index.html
</Directory>
```

[相关链接][1]

[1]:https://blog.csdn.net/leshami/article/details/78461590