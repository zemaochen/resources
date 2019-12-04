# PicGo

![](https://raw.githubusercontent.com/zemaochen/images/master/img/20191204175705.png)

- 这是一款图片上传的工具，目前支持微博图床，七牛图床，腾讯云，又拍云，GitHub等图床，未来将支持更多图床。
- 本地的文件，或者剪切板上面的截图发送图床，然后生成在线图片的链接，这样就可以让Markdown文档飞起来了，走到哪就可以用到哪

## git配置
- 首先你要有一个git帐号去注册([git](https://github.com/))

- 新建一个代码仓库

  

  ![](https://raw.githubusercontent.com/zemaochen/images/master/img/20191204175041.png)

  

  ![](https://raw.githubusercontent.com/zemaochen/images/master/img/20191204175517.png)

- 生成一个Token用于操作GitHub repository
> 步骤1 头像--->settings 

 ![](https://raw.githubusercontent.com/zemaochen/images/master/img/20191204183414.png)

> 步骤二 developer setting

 ![](https://raw.githubusercontent.com/zemaochen/images/master/img/20191204183521.png)

> 步骤三 Personal access tokens-->generate new token

![](https://raw.githubusercontent.com/zemaochen/images/master/img/20191204184821.png)

> 生成令牌(点最下面genarate。。。)

![](https://raw.githubusercontent.com/zemaochen/images/master/img/20191204185328.png)

> 查看令牌：

![](https://raw.githubusercontent.com/zemaochen/images/master/img/20191204185716.png)

748e1089c0799d41f5db14f626f8a44a580e973e

## 工具设置

- 去下载picgo    [链接](https://github.com/Molunerfinn/PicGo)

- 安装

- 配置

- ![](https://raw.githubusercontent.com/zemaochen/images/master/img/20191204190336.png)


> 设定仓库名的时候，是按照“账户名/仓库名的格式填写”
> 分支名统一填写“master”
> 将之前的Token黏贴在这里
> 存储的路径可以按照我这样子写，就会在repository下创建一个“img”文件夹
> 自定义域名的作用是，在上传图片后成功后，PicGo会将“自定义域名+上传的图片名”生成的访问链接，放到剪切板上https://raw.githubusercontent.com/用户名/RepositoryName/分支名，，自定义域名需要按照这样去填写

- 修改快捷键

  ![](https://raw.githubusercontent.com/zemaochen/images/master/img/20191204191121.png)

将上面的步骤都设置好之后，就可以让自己的Markdown文档飞起来了，每次截图之后，都可以按一下`ctrl+shift+c`，这样就会将剪切板上面的截图转化为在线网络图片链接(可以直接粘贴链接)