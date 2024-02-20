+++
title = "The text file that runs the internet"
description = ""
date = 2024-02-20T14:40:42Z
updated = 2024-02-20T14:40:42Z
authors = ["David Pierce"]
weight = 0
draft = false
aliases = []
in_search_index = true
[extra]
original_url = "https://www.theverge.com/24067997/robots-txt-ai-text-file-web-crawlers-spiders"
source = "The Verge"
comment = ""
[taxonomies]
focus_blend_categories = ["Tech Trends"]
focus_blend_tags = ["AI"]
+++

For most websites, this was an easy trade. “Google is our most important spider,” says Medium CEO Tony Stubblebine. Google gets to download all of Medium’s pages, “and in exchange we get a significant amount of traffic. It’s win-win. Everyone thinks that.” This is the bargain Google made with the internet as a whole, to funnel traffic to other websites while selling ads against the search results. And Google has, by all accounts, been a good citizen of robots.txt. “Pretty much all of the well-known search engines comply with it,” Google’s Mueller says. “They’re happy to be able to crawl the web, but they don’t want to annoy people with it… it just makes life easier for everyone.”

对于大多数网站来说，这是很容易的交易。"Medium 首席执行官托尼 - 斯塔布宾（Tony Stubblebine）说："谷歌是我们最重要的蜘蛛。谷歌可以下载 Medium 的所有网页，"作为交换，我们获得了大量的流量。这是双赢。每个人都这么认为。这就是谷歌与整个互联网达成的协议，在向其他网站输送流量的同时，还在搜索结果中出售广告。从各方面来看，谷歌都是 robots.txt 的好公民。"谷歌的穆勒说："几乎所有知名的搜索引擎都遵守了这一规定。"他们很高兴能够抓取网页，但也不想因此惹恼别人......这只是让大家的生活变得更轻松。

In the last year or so, though, the rise of AI has upended that equation. For many publishers and platforms, having their data crawled for training data felt less like trading and more like stealing. “What we found pretty quickly with the AI companies,” Stubblebine says, “is not only was it not an exchange of value, we’re getting nothing in return. Literally zero.” When Stubblebine announced last fall that Medium would be blocking AI crawlers, he wrote that “AI companies have leached value from writers in order to spam Internet readers.”

不过，在过去一年左右的时间里，人工智能的兴起颠覆了这一等式。对于许多出版商和平台来说，让他们的数据被抓取以获取训练数据，感觉不像是交易，更像是偷窃。"Stubblebine 说："我们很快就发现，人工智能公司不仅没有进行价值交换，我们也没有得到任何回报。简直就是零。"去年秋天，当斯塔伯宾宣布 Medium 将屏蔽人工智能爬虫时，他写道："人工智能公司从作家那里攫取了价值，以便向互联网读者发送垃圾邮件"。

It’s not just publishers, either. Amazon, Facebook, Pinterest, WikiHow, WebMD, and many other platforms explicitly block GPTBot from accessing some or all of their websites. On most of these robots.txt pages, OpenAI’s GPTBot is the only crawler explicitly and completely disallowed. But there are plenty of other AI-specific bots beginning to crawl the web, like Anthropic’s anthropic-ai and Google’s new Google-Extended. According to a study from last fall by Originality.AI, 306 of the top 1,000 sites on the web blocked GPTBot, but only 85 blocked Google-Extended and 28 blocked anthropic-ai.

不仅仅是出版商。亚马逊、Facebook、Pinterest、WikiHow、WebMD 和许多其他平台都明确禁止 GPTBot 访问其部分或全部网站。在这些 robots.txt 页面中，OpenAI 的 GPTBot 是唯一一个被明确完全禁止的爬虫。但也有很多其他人工智能专用机器人开始抓取网络，比如 Anthropic 的 anthropic-ai 和谷歌的新版 Google-Extended。根据 Originality.AI 去年秋天进行的一项研究，网络上排名前 1000 位的网站中有 306 个屏蔽了 GPTBot，但只有 85 个屏蔽了 Google-Extended，28 个屏蔽了 anthropic-ai。

Even as AI companies face regulatory and legal questions over how they build and train their models, those models continue to improve and new companies seem to start every day. Websites large and small are faced with a decision: submit to the AI revolution or stand their ground against it. For those that choose to opt out, their most powerful weapon is an agreement made three decades ago by some of the web’s earliest and most optimistic true believers. They believed that the internet was a good place, filled with good people, who above all wanted the internet to be a good thing. In that world, and on that internet, explaining your wishes in a text file was governance enough. Now, as AI stands to reshape the culture and economy of the internet all over again, a humble plain-text file is starting to look a little old-fashioned.

尽管人工智能公司在如何建立和训练模型方面面临着监管和法律问题，但这些模型仍在不断改进，似乎每天都有新公司成立。大大小小的网站都面临着一个抉择：是屈从于人工智能革命，还是坚守阵地与之对抗。对于那些选择退出的网站来说，他们最有力的武器是三十年前由一些网络最早和最乐观的忠实信徒达成的协议。他们相信，互联网是个好地方，到处都是好人，他们最希望互联网是个好东西。在那个世界，在那个互联网上，用文本文件解释你的愿望就足够了。现在，随着人工智能重新塑造互联网的文化和经济，一个不起眼的纯文本文件开始显得有点过时了。
