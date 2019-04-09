#### 构建博客网站过程中遇到的一些问题

在编写博客的过程中遇到一些问题，在这里汇总

##### 如何在博文中添加图片

```shell
cd /code/myblog/public

mkdir images
```

将需要添加的图片放到上面创建的 images 目录中，当然也可以再创建子文件夹，把图片放到对应的目录中

例如在 images/blogs 文件夹中有一个 test.jpg 图片文件，那么在博文中用下面的方式引入

```md
![test image](/images/blogs/test.jpg "test image")
```

这样就可以正常引入图片了