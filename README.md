# Geyepa_openlib 给爷爬 开放库
Geyepa 给爷爬 — 自动化互联网信息爬取系统 Automated Internet Information Crawling System

Geyepa 还在开发中，主程序不打算开源，但会开源 Geyepa 的部分库 Geyepa_openlib

欢迎一起开发 Geyepa_openlib，如果你希望和我一起开发 Geyepa 可以联系我
你可以通过GitHub找到我的联系方式，或者直接给我发送邮件 jimmy_kmi@outlook.fr

## Geyepa 和 Geyepa_openlib 有什么关系
Geyepa_openlib 是 Geyepa 的其中一部分原创函数库，是 Geyepa 的核心代码的一部分。目前计划会包括连接数据库、分析网页分支、获取网页和解码。
Geyepa 由于我担心主程序在公开后可能会带来一定的风险，被改装成无视爬虫协议的爬虫程序，并且由于 Geyepa 主要功能是定向爬取，在操作不当时可能会对特定网站造成大量请求影响网站正常进行，所以在可以确保一切工作稳定和可控之前暂时不开源。
如果你希望开发一个爬虫程序，Geyepa_openlib或许能帮上你的大忙

## Geyepa 即将能做什么
这个程序用于实时收集并分析互联网的数据并存放在你的数据库中，在你需要某些信息的时候你可以输入一些关键词和关键信息，等待一段时间后即可在数据库查询并查看程序根据你所输入的信息在互联网上找到什么。
数据呈现的形式将多种多样，而且不只是展现数据列表，而且系统会尽力找到这些数据之间的关联以及关键信息。
这个程序可以在多个服务器上部署，并同时工作和自动分配任务，会对当下的任务列表分出紧急程度。
这个程序可以执行多样自动化，例如定时查询并推送某些类型的信息，甚至用于新闻定时摘要和推送。

我将尽力考虑使此程序的可拓展性提高，并考虑分布式部署。

**[!] 我希望专注于开发上，如果你希望帮助我翻译注释和文档，我将十分感谢！**

## 开源协议和法律法规
### 合法性
本程序遵从中国法律与欧洲个人信息保护相关法律，无论用于公开、个人使用，都请勿用于任何非法用途或用于协助开发任何非法程序。
### 开源协议
你可以使用本程序进行任何符合中国法律与欧洲个人信息保护相关法律的商业活动，甚至修改、闭源。但当你使用本代码后，无论如何修改或再发布**均需著名原作者并提供链接到这里**。

## 怎么跑起来
你需要一个SQL数据库以存储爬取到的数据，和一个Redis用于存放爬取任务。

程序还没开发完，想peach捏
