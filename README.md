# 本博客的简介
这是我，一个不懂IT技术,但却有点热爱的人，在互联网茫茫大海中，由于各种机缘巧合，我遇到了github，也遇到了码志的博客模版，由此我想建立一个人的数字生命，这世界我来过，可是有多少人知道呢？就像远古时期的一个人，会在石头上刻一些文字，已保留一点自己的存在感，我也一样。所以我会把我写过的网章都收集放在这个博客上，因为我认为github的生命力是很顽强的。当然我也会留一份底稿在我的电脑上，并且打印一份出来。其目的是让自己有一种充实感，让我的后代想了解我的时候，能够有一个渠道。这个博客，我想说什么就可以说什么，因为它没有什么影响力，也大概率不会有身边人知道。这是国内博客平台不能具备的。当然我不会用这个平台去鼓吹什么，我对那些没兴趣，我只是想默默的说出自己的一点感想，因为我是孤独的，我是社恐的，现实世界很难随便找一人说自己的想法，别人会不认同，会反感，但自己作为生物人，也必然有表达倾诉的本能，因此在一个没人知道的地方，自言自语，或许是一种不错的办法。
我的文章主要涉及生命的意义，对现代医疗制度的看法，投资，财务自由，教育等等。
感谢模版提供者，我不会对网站做很多修改，如果出现一些技术类的文章，那应该都是我没删掉的模版自带的文章，当然我会尽量删除。 
# 以下为模版内容，暂不删除，以防后用志


我的个人博客：<https://mazhuang.org>，欢迎 Star 和 Fork。

## 概览

<!-- vim-markdown-toc GFM -->

* [效果预览](#效果预览)
* [Fork 指南](#fork-指南)
* [使用文档](#使用文档)
* [经验与思考](#经验与思考)
* [联系我](#联系我)
* [致谢](#致谢)

<!-- vim-markdown-toc -->

## 效果预览

**[在线预览 &rarr;](https://mazhuang.org)**

![screenshot home](https://mazhuang.org/assets/images/screenshots/home.png)

## Fork 指南

Fork 本项目之后，还需要做一些事情才能让你的页面「正确」跑起来。

1. 正确设置项目名称与分支。

   按照 GitHub Pages 的规定，名称为 `username.github.io` 的项目的 master 分支，或者其它名称的项目的 gh-pages 分支可以自动生成 GitHub Pages 页面。

2. 修改域名。

   如果你需要绑定自己的域名，那么修改 CNAME 文件的内容，并参考 [配置 GitHub Pages 站点的自定义域](https://docs.github.com/cn/pages/configuring-a-custom-domain-for-your-github-pages-site) 做好配置；如果不需要绑定自己的域名，那么删掉 CNAME 文件。

3. 修改配置。

   网站的配置基本都集中在 \_config.yml 文件中，将其中与个人信息相关的部分替换成你自己的，比如网站的 url、title、subtitle 和第三方评论模块的配置等。

   **评论模块：** 目前支持 disqus、gitment、gitalk、utterances、beaudar 和 giscus，选用其中一种就可以了，推荐使用 giscus。它们各自的官方配置指南链接在 \_config.yml 文件的 Comments 一节里都贴出来了，请参考官方指南配置。

   **注意：** 如果使用 disqus，因为 disqus 处理用户名与域名白名单的策略存在缺陷，请一定将 disqus.username 修改成你自己的，否则请将该字段留空。我对该缺陷的记录见 [Issues#2][3]。

4. 删除我的文章与图片。

   如下文件夹中除了 template.md 文件外，都可以全部删除，然后添加你自己的内容。

   * \_posts 文件夹中是我已发布的博客文章。
   * \_drafts 文件夹中是我尚未发布的博客文章。
   * \_wiki 文件夹中是我已发布的 wiki 页面。
   * \_fragments 文件夹中是我已发布的短文片段。
   * images 文件夹中是我的文章和页面里使用的图片。

5. 修改「关于」页面。

   pages/about.md 文件内容对应网站的「关于」页面，里面的内容多为个人相关，将它们替换成你自己的信息，包括 \_data 目录下的 skills.yml 和 social.yml 文件里的数据。

   skills.yml 和 social.yml 里内容的含义可以参考：[_data 目录下的 yml 文件内容含义](https://mazhuang.org/2020/05/03/blog-template-qna/#_data-%E7%9B%AE%E5%BD%95%E4%B8%8B%E7%9A%84-yml-%E6%96%87%E4%BB%B6%E5%86%85%E5%AE%B9%E5%90%AB%E4%B9%89)。

## 使用文档

- [本博客模板常见问题 Q & A](https://mazhuang.org/2020/05/03/blog-template-qna/)。

- 在本地预览博客效果可以参考 [Setting up your Pages site locally with Jekyll][2]。

## 经验与思考

* 排版建议遵照一定的规范，推荐 [中文文案排版指北（简体中文版）][1]。

* 简约，尽量每个页面都不展示多余的内容。

* 有时一图抵千言，有时可能只会拖慢网页加载速度。

* 言之有物，不做无痛之呻吟。

* 如果写技术文章，那先将技术原理完全理清了再开始写，一边摸索技术一边组织文章效率较低。

* 杜绝难断句、难理解的长句子，如果不能将其拆分成几个简洁的短句，说明脑中的理解并不清晰。

* 可以学习一下那些高质量的博主，他们的行文，内容组织方式，有什么值得借鉴的地方。

## 联系我

如果对本博客模板或者内容有任何建议，可以通过 [Issues](https://github.com/mzlogin/mzlogin.github.io/issues) 或者微信公众号「闷骚的程序员」与我取得联系。

<img width="192px" height="192px" src="https://mazhuang.org/assets/images/qrcode.jpg"/>

## 致谢

本博客外观基于 [DONGChuan](https://dongchuan.github.io) 修改，感谢！

[1]: https://github.com/mzlogin/chinese-copywriting-guidelines
[2]: https://help.github.com/articles/setting-up-your-pages-site-locally-with-jekyll/
[3]: https://github.com/mzlogin/mzlogin.github.io/issues/2
