🎉 使用 Github Pages 和 Hexo 搭建的个人博客

链接：http://cq-hsiao.github.io

> <font size=4><p>一次偶然的机会发现了Hexo这个博客框架，自己花了几天时间也顺利把博客搭建了起来。</p></font>

## Hexo简介

> Hexo是一款基于Node.js的静态博客框架，依赖少易于安装使用，使用 Markdown（或其他渲染引擎）解析文章可以方便地生成静态网页托管在GitHub和Coding上，确实是一个快速、简洁且高效的博客框架。大家可以进入hexo官网进行详细查看，因为Hexo的创建者是台湾人，对中文的支持很友好，可以选择中文进行查看。
<!--more-->
## 如何搭建
<font size=3>
自己也是从网上查询教程一步一步搭建的。这里推荐一个比较全面的教程。
[https://blog.csdn.net/sinat_37781304/article/details/82729029](https://blog.csdn.net/sinat_37781304/article/details/82729029 "hexo史上最全搭建教程")

自己使用的主题是[hexo-theme-melody](https://molunerfinn.com/hexo-theme-melody-doc/zh-Hans/ "hexo-theme-melody使用文档")，使用了pug模板引擎渲染静态页面，刚开始阅读和修改起来还是有些吃力的，自己也琢磨了一会才大概了解。

Hexo也集成了很多功能，这个主题支持RSS订阅功能、评论系统、分享系统、搜索系统、统计分析、动画效果等。几乎修改主题配置文件就可以实现了。

还想要美化自己的博客或者添加各种有趣好玩的功能和特效，比如看板娘、动态彩带。自己网上找相应的教程就好了。
[https://blog.csdn.net/qq_36759224/article/details/85420403](https://blog.csdn.net/qq_36759224/article/details/85420403 "Hexo 博客优化之博客美化")

## 个人修改
增加valine评论系统，搜索，百度统计，字数统计，不蒜子访问日志(UV和PV)，RSS订阅等功能
<font color=#3090e4>(注：百度统计的代码和valine的appid和key需自行填写配置）</font>

1. 修改和增添样式，增加看板娘，动态彩带等。修改背景图只占满头部而不是整个页面；
2. 解决增加看板娘后不蒜子统计数据不显示BUG；
3. 将阅读数统计改成放在文章标题下而不是页尾；
4. 页脚自定义文本增加网站运行时间统计；
</font>