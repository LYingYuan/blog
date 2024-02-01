+++
title = "Why is machine learning 'hard'?"
description = ""
date = 2024-01-24T13:57:16Z
updated = 2024-02-01T11:03:15Z
authors = ["S. Zayd Enam"]
weight = 0
draft = false
aliases = []
in_search_index = true
[extra]
original_url = "https://ai.stanford.edu/~zayd/why-is-machine-learning-hard.html"
source = "Stanford AI Lab"
comment = ""
[taxonomies]
focus_blend_categories = ["Tech Trends"]
focus_blend_tags = ["Machine Learning"]
+++

This difficulty is often not due to math - because of the aforementioned frameworks machine learning implementations do not require intense mathematics. An aspect of this difficulty involves building an intuition for what tool should be leveraged to solve a problem. This requires being aware of available algorithms and models and the trade-offs and constraints of each one. By itself this skill is learned through exposure to these models (classes, textbooks and papers) but even more so by attempting to implement and test out these models yourself. However, this type of knowledge building exists in all areas of computer science and is not unique to machine learning. Regular software engineering requires awareness of the trade offs of competing frameworks, tools and techniques and judicious design decisions.

这种困难往往不是因为数学--因为上述框架的机器学习实现并不需要高深的数学。这种困难的一个方面涉及建立一种直觉，知道应该利用什么工具来解决问题。这需要了解可用的算法和模型，以及每种算法和模型的权衡和限制。这种技能本身可以通过接触这些模型（课程、教科书和论文）来学习，但更多的是通过自己尝试实现和测试这些模型来学习。不过，这种知识积累存在于计算机科学的所有领域，并非机器学习所独有。常规的软件工程需要了解相互竞争的框架、工具和技术的利弊，并做出明智的设计决策。

The difficulty is that machine learning is a fundamentally hard debugging problem. Debugging for machine learning happens in two cases: 1) your algorithm doesn't work or 2) your algorithm doesn't work well enough. What is unique about machine learning is that it is ‘exponentially’ harder to figure out what is wrong when things don’t work as expected. Compounding this debugging difficulty, there is often a delay in debugging cycles between implementing a fix or upgrade and seeing the result. Very rarely does an algorithm work the first time and so this ends up being where the majority of time is spent in building algorithms.

困难在于，机器学习从根本上说是一个难以调试的问题。机器学习的调试有两种情况：1）你的算法不工作；或 2）你的算法工作得不够好。机器学习的独特之处在于，当事情不能按预期运行时，要找出问题所在的难度是 "指数级 "的。除了调试难度之外，从实施修复或升级到看到结果之间的调试周期也经常会出现延迟。很少有算法第一次就能正常工作，因此在构建算法的过程中，大部分时间都花在了调试上。

The second compounding factor that complicates machine learning debugging is long debugging cycles.

导致机器学习调试复杂化的第二个复杂因素是调试周期长。
