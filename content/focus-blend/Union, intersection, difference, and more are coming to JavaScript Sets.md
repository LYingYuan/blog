+++
title = "Union, intersection, difference, and more are coming to JavaScript Sets"
description = ""
date = 2024-02-20T13:44:55Z
updated = 2024-02-20T13:44:55Z
authors = ["Phil Nash"]
weight = 0
draft = false
aliases = []
in_search_index = true
[extra]
original_url = "https://www.sonarsource.com/blog/union-intersection-difference-javascript-sets/"
source = "Sonar Source"
comment = ""
[taxonomies]
focus_blend_categories = ["Tech Trends"]
focus_blend_tags = ["JavaScript"]
+++
Sets are collections of values where each value may only appear once. In the ES2015 version of the Set, the available functionality revolved around creating, adding to, removing from, and checking the membership of a Set. If you wanted to operate on or compare more than one set, you had to write your own functions. Thankfully, TC39—the committee established to work on the ECMAScript spec—and the browsers have been working on this. We are now seeing functions like union, intersection and difference in JavaScript implementations.

集合是值的集合，其中每个值只能出现一次。在 ES2015 版本的 Set 中，可用功能主要围绕创建、添加到 Set 中、从 Set 中删除以及检查 Set 的成员资格。如果您想对多个集合进行操作或比较，就必须编写自己的函数。值得庆幸的是，为制定 ECMAScript 规范而成立的 TC39 委员会和浏览器一直在努力解决这一问题。我们现在可以在 JavaScript 实现中看到 union、intersection 和 difference 等函数。

You can check if an element is a member of the Set with the has function. One of the benefits of a Set is that this check can be done in constant time (O(1)), whereas the time to check if an element is in an Array varies by the length of the Array (O(n)). Using Sets for tasks like this is a clean way to write intentional efficient code.

您可以使用 has 函数检查一个元素是否是 Set 的成员。Set 的好处之一是，这种检查可以在恒定时间内完成 (O(1))，而检查元素是否在 Array 中的时间则取决于 Array 的长度 (O(n))。使用 Set 来完成类似任务，是编写有意高效代码的简洁方法。

