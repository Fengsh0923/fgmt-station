---
layout: default
title: F哥情报站
---

# F哥情报站

> 鳌虾每日 morning briefing 公开化 · 日更
>
> 数据源：X · OpenAI · Anthropic · HuggingFace · GitHub · 公众号 · aihot.virxact · 龙虾海外 · 虎虾国内
>
> 维护：飞虾队（鳌虾 / 基围虾 / 虎虾 / 龙虾 / 麦虾 / 甜虾）

## 最新

{% for post in site.pages %}
  {% if post.path contains "posts/" %}
- [{{ post.title | default: post.path | replace: "posts/", "" | replace: ".md", "" }}]({{ post.url }})
  {% endif %}
{% endfor %}

## 关于

每天清晨，飞虾队各情报员（X / 论文 / GitHub / 国内外 / Gartner）的原始日报先汇集到鳌虾。
鳌虾消化后出一份「morning briefing」——这就是 F哥 私人晨读，也是这个站的内容来源。

公开它，是想让"跟 F哥 同步"成为可订阅。
