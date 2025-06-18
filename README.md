# hexo
开始记笔记，本地部署个人博客，并且成功访问网页：

首先拉取项目，这个项目是一个hexo的标准项目：

然后上传到自己的github上面，最好新建一个库：
![[Pasted image 20250618145302.png]]


拉取butterfly模板项目：
![[Pasted image 20250618145027.png]]

```bash
git clone -b master https://gitee.com/immyw/hexo-theme-butterfly.git themes/butterfly
```
![[Pasted image 20250618145353.png]]

这是github新项目的基本操作，需要加入一个readme.md文件，然后把这个文件加到github项目当中，然后上传整个项目，并且确定branch也就分支是main分支，防止混淆。

```bash
git branch -M main
```
然后这个项目依赖于插件，下面是插件下载的指令：

![[Pasted image 20250618145533.png]]

```bash
npm install hexo-renderer-pug hexo-renderer-stylus --save
```

执行这个操作之后，需要把_config.yml文件当中的主题，改为butterfly：
![[Pasted image 20250618145649.png]]

下面就可以在本地运行，查看效果了：

![[Pasted image 20250618145715.png]]
![[Pasted image 20250618145732.png]]