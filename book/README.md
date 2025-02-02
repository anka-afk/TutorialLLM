# 前言

2022年底至今，大模型席卷了AI（人工智能）的几乎所有领域。不懂点大模型知识，彷佛就和AI脱了节。

如果你曾尝试过搜索大模型入门教程，会发现大部分在教你如何用大模型，而不是如何制作大模型。这倒合情合理，因为当下的市场需要广大开发者利用国内外领先的大模型API构建应用，而不是另起炉灶训练自己的大模型。2023年开始，中国大模型厂家百花齐放，但真正能撑到泡沫褪去的估计不太多。

不过，这并不意味着我们不需要学习大模型的内部原理。作为开发者，你应该明白了解技术的底层机制才能更好地运用它。但由于大模型本身的复杂度，以及训练所需的昂贵代价，网上系统介绍大模型底层原理的教程很少。仅有的一些文章博客理论性较强，对初学者不甚友好。在我转型学习大模型的过程中，这些困难让我决心编写这个教程，希望能帮助到更多人。

如果你也想知道

* 大模型是如何设计出来的？
* 构成大模型的基本结构是什么？
* 模型的训练到底是怎么一回事？
* 什么是预训练（pretrain）、微调（finetune）、对齐（alignment）？
* 怎么用最简单的方法自己训练一个大模型出来？

那么本书将是你的最佳选择。

本书的内容面向广大初学者，只要具备一定数学和编程基础，阅读本文就不会有任何障碍。即便不懂编程、讨厌数学，你也仍然能从中获得极大收获。在整个过程中，我会以第一性原理为指导，用最通俗的语言引导读者从零开始一步步设计出大模型的所有模块。为了紧密结合理论和实践，我们将使用一个微缩版的大模型，它可以运行在任何一台电脑上。文中使用的案例专为中国读者设计，保证所有人一看就能明白我们在做什么。

需要强调的是，本书并不包含任何实用性的大模型训练技巧，也不会过于深入细节。我希望用通俗易懂的语言，结合实际可运行的程序，让大家对大模型的工作原理有一个全面的体会。本文的配套源代码位于GitHub的[TutorialLLM](https://github.com/jingedawang/TutorialLLM)仓库，供读者免费取用。

如果你读到任何无法理解的内容，请在当前阅读平台或GitHub的Issue中留言告知。你的反馈至关重要，请和我一起完善这部教材，帮助更多需要的人。
