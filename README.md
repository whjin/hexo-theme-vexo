# hexo-theme-vexo

[hexo-theme-vexo](https://github.com/whjin/hexo-theme-vexo) 是一款类 [Vue.js](https://cn.vuejs.org) 官网主题，特色是简洁明快。

# 简介 #

![](http://file.muyutech.com/vexo.png)

# Demo #

这个我的个人博客，可查看 [live demo](https://whjin.github.io/)

# 安装使用 #

1、先安装最新版本的 `node.js`、`Git base`以及 [Hexo](http://ibruce.info/2013/11/22/hexo-your-blog/)

2、把 `Hexo` 基础模板完成后，进入 `themes` 文件夹，下载主题，尽量使用 **SSH** 

    git clone git@github.com:whjin/hexo-theme-vexo.git

3、修改 `_config.yml` 里面的配置为自己的内容。

# 全局配置 #

因为 **Hexo** 外层全局配置也是非常重要且关键的，考虑到这点，我把全局配置的文件内容上传到 **Github**，点击[这里](https://github.com/whjin/myBlog)查看。

# 更新升级 #

有时间我会修改或更新这个主题，更新内容会同步到这个 **README.md**，大家可以查看更新项，如果喜欢，可以选择更新一下。进行主题文件夹 `cd themes/vexo`

    git pull

# 文章 #

文章的页头是这样的：

    ---
    title: 
    date: 2017-10-06 09:23:18
    category: ["cate1"]
    tags: ["tag1","tag2"]
    ---
    这里可以用 more 进行分割，作为摘要显示。
    <!--more-->

# 更新日志 #

2017/12/14 0:01:16 

# 主题特点 #

这个 **hexo** 主题是在[原版](https://github.com/yanm1ng/hexo-theme-vexo)的基础上加上自己偏爱的元素，基本上没有做太多的修改， 只需要在配置文件 `_config.yml` 里面填入个人项即可。包含的内容有：

1. [百度统计](https://tongji.baidu.com/web/welcome/login)，这个已经集成在 `theme/layout/page.ejs`页面，只需要参照百度统计的教程把配置内容更换成自己的就可以了。
2. 评论留言使用的是[畅言](http://changyan.kuaizhan.com/)，注册畅言需要进行网站备案，可以使用[这里](http://bubuzou.com/)的备案号填写资料，非常方便。有什么不明白的地方可以提 `Issues`，我经常登录 **Github**，有时间会提供详细解答。
3. SEO、分享都在 `theme/layout/page.js` 页面。

# 赞赏 #

主题添加了赞赏页面，只需要更换成自己的二维码即可，在 `themes/source/css/images` 文件夹里进行替换。

想要使用原版样式可以参考[这里](https://github.com/yanm1ng/hexo-theme-vexo)

# 页脚统计 #

页面使用了 [不蒜子](http://busuanzi.ibruce.info/) 进行访问量统计，只需要改为自己的内容即可。

更多内容查看 [不如](http://ibruce.info/)

# About #

- 喜欢这个主题的朋友请给个 **Star**，**Fork**或者关注一下。
- 有使用上的疑问，可以提 `Issues`。
- 感谢 [@yanm1ng](https://github.com/yanm1ng)，[@Evan You](https://github.com/yyx990803)，[@Hexo](https://hexo.io/)，以及[@whjin](https://github.com/whjin) 对本主题的贡献！

# LICENSE #

[MIT](https://opensource.org/licenses/MIT)
