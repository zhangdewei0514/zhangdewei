---
layout: page
title: 关于
description: 写点什么？
keywords: Zhang Dewei, 张德伟
comments: true
menu: 关于
permalink: /about/
---

张德伟，80年代初生人，江苏扬州。

平庸是我的标签。

社恐、不善表达、笨手笨脚。

朴素、非必要不花钱。

收入-支出=结余，喜欢降低支出，喜欢增加被动收入，FIRE运动的仰慕者。

一些技能：
sony电纸书刷机直接看epub电子书（用软件转换后）
看透财富本质，自认为可以帮助别人摆脱经济苦恼（教育、医疗、生活有多少钱是有效支出呢？）
办公小达人（20年了，office,vba,图像处理还能没点心得？）

最喜欢在图书馆，阳光洒在身上，听着音乐，阅读亦或写点什么，让自己的生命流淌在思绪中。

个人关键字：内向、闷、自行车出行、公交车、瘦、体弱、亚健康、爱看书、看电影、写文章、投资、炒股、躺平、自由散漫

## 联系

<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
{% if site.url contains 'mazhuang.org' %}
<li>
微信公众号：<br />
<img style="height:192px;width:192px;border:1px solid lightgrey;" src="{{ site.url }}/assets/images/qrcode.jpg" alt="张德伟" />
</li>
{% endif %}
</ul>


## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
