OpenStack
=========

《OpenStack开源云王者归来》一书所附代码及资料。本书采用OpenStack Grizzly版本。

在使用资料包之前，应该选择一种方式：

- 创建链接文件，节省空间，但是不能改变目录树相对结构。
- 创建拷贝文件，不节省空间，但是每个章节可以单独提取出来使用，不需要依赖于整个资料包。


# 创建链接文件
由于很多章节所引用的资料都是相同的。这些资料都放置于安装脚本的同级目录。如果每个章节都采用相同的资料，资料包的体积会变得相当大。一种简单的解决办法就是将这些资料放置于公共目录，然后在每个章节中创建链接文件。

创建链接文件的方法：
* 下载完成之后，应该运行./create_link.sh

# 下载方式
除了使用git下载之外，还可以使用百度云上的公有链接下载此资源。
http://pan.baidu.com/s/1jGqoPhG


# 创建拷贝

创建链接文件的方法，需要保持整个资料包的目录相对结构不变化。如果需要单独使用某个章节。这时需要将创建链接文件的方式变为拷贝。

- 运行./create_link.sh
- 到chap0x章节下，将链接目录、链接文件，采用拷贝的方式复盖。

# 联系方式
有任何问题，请联系作者 jumail@qq.com

为了更加方便交流，关收OpenStack书籍的任何问题，可加入QQ群345596547即OpenStack品书会。

# 常见问题

由于能力有限，亦加时过境迁，编写的内容总会出现各种错误，请注意关注[常见问题](https://github.com/JiYou/openstack/blob/master/qa.md)。

# 搭建虚拟机

## step 1
请参照[vm-install-guide.docx](./vm-install-guide.docx)

## step 2
请参考[常见问题](https://github.com/JiYou/openstack/blob/master/qa.md)建离线源方法。

## 注意
做OpenStack实验用的虚拟机，尽量不要做其他额外的实验，否则依赖包比较难以解决。


## 所有资源
本书用到的所有资源都可以从百度云中下载：http://pan.baidu.com/s/1gdzixz1 。
