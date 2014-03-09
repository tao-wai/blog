title: technology
date: 2014-03-02 20:55:57
tags: [标签,说明]
categories: 技术
---
### 如何写博客

本博客基于hexo+git开发，[hexo](http://zespia.tw/hexo)是一个基于Node.js的静态博客程序，听说其编译上百篇文字只需要几秒，出自台湾大学生[tommy351](https://twitter.com/tommy351)之手，优点在于快，小，轻，关键是基于Node，顿时高大上起来有木有。主题是[pacman](http://yangjian.me/workspace/introducing-pacman-theme/)，为什么选它因为当时百度搜索第一个，友情链接链接里有[hexo官方网站](http://zespia.tw/hexo)。评论系统用的[多说](http://duoshuo.com/)，大家最好注册一下账号然后我加进管理员，简介到此，下面看步骤：
 1. 安装hexo:  npm install hexo -g
 2. git clone git@github.com:tao-wai/blog.git
 3. cd 到库的根目录下执行，hexo init blog
 4. 开始写博文， hexo new "New Post"(注意要在categories里添加类别，不然上面导航栏里找不到)
 5. 写完本地查看 hexo server (127.0.0.1:4000)
 6. 发布:hexo deploy(自动推送到git上，注意需要配置第二个rsa，参考[多个github帐号的SSH key切换](http://omiga.org/blog/archives/2269)，建议host2为wai.github.com)


 > **NOTE:** 
 > - 如果大家碰到什么奇怪的错误，就先hexo clean,再hexo generate一下.
 > - 如果大家又碰到什么奇怪的错误，就先删掉.deploy文件夹，再hexo clean,再hexo generate一下.
 > - 写完了别忘了push一下blog.git，这样就不会把你的覆盖掉了。。

系统源码在[此处](https://github.com/tao-wai/blog)


 ----------


enjoy it!
--------------