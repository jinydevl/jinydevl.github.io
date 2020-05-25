---
layout: page
title: About
description: Stay Hungry, Stay Foolish.
keywords: Yang Jing, 杨璟
comments: true
menu: 关于
permalink: /about/
---

我是杨璟，码而生，码而立。

仰慕「优雅编码的艺术」。

坚信熟能生巧，努力改变人生。

## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
