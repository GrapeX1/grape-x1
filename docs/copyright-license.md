---
title: 版权协议
author: GrapeX1
description: 开放源代码和知识共享的版权协议，可以保护创作者。
date: 2024-12-29
time: 22:04
tags:
  - license
---

## 开源协议

开源协议，又称开源许可证（[open-source license](http://en.wikipedia.org/wiki/Open-source_license)），又称开源许可协议（licensing agreement），又称开源授权。

许可是什么？当你为你的产品签发许可，你是在出让自己的权利，但你仍然拥有版权和专利（如果申请了的话）。许可的目的是，**向使用你产品的人提供一定的权限**。

开源许可证是为保护[自由软件](https://www.gnu.org/philosophy/free-sw.html)原作者的相关知识产权，在作者与用户之间设立的一种虚拟合同，或者称之为授权方式。其中的条款内容，就是用来限制软件使用者的使用方式等。他人如有违反许可证，作者有权利发起诉讼，维护自身权益。

开源许可证的部分优点：

- 使开发者很容易向一个项目贡献自己的代码。
- 保护你原始作者的身份，使你至少获得认可。
- 阻止其它人将某个产品据为己有。

引用[@Phodal 的解释开源许可证 svg 图片](https://github.com/phodal/licenses)：

![Open-source License Explains](https://raw.githubusercontent.com/phodal/licenses/refs/heads/gh-pages/license.svg)

葡萄诚意作为「开源狂热粉」，决定在公开程序代码（开放源代码）时通常使用 GNU GPLv3（GNU 通用公共许可证版本 3）。

### 使用 GNU 许可证

此小节参考了《[如何在你的软件中使用 GNU 许可证](https://www.gnu.org/licenses/gpl-howto.html)》。

以下总结了在选择按照 GNU 许可证发布程序时，你需要做的事项：

- 从你的雇主或学校获取一份[版权免除声明](https://www.gnu.org/licenses/gpl-howto.html#copyright-disclaimer)。
- 为每个文件提供适当的版权声明。确保[用户可用的许可证版本被清晰地标识出来](https://www.gnu.org/licenses/identify-licenses-clearly.html)。
- 每个文件都要有许可证声明。
- 添加一个带有 GNU GPL 或 GNU AGPL 副本的 COPYING 文件。
- 如果使用了 GNU LGPL，那么再添加一个带有 GNU LGPL 副本的 COPYING.LESSER 文件。
- （可选项）程序开始时显示一个声明。
- （如果使用 AGPL）让程序带有提供源代码的选项。

#### 版权声明和许可证声明

每个程序都要添加两个单元：[版权声明](https://www.gnu.org/licenses/gpl-howto.html#copyright-notice)（比如「Copyright 2024 GrapeX1」）和拷贝授权声明（即是复制许可声明，又称[许可证声明](https://www.gnu.org/licenses/gpl-howto.html#license-notices)），说明本程序按照 GNU 通用公共许可证（或 LGPL、Affero GPL）的条款发布。

当 GrapeX1 使用 GNU GPLv3 发布 grape-x1 程序——在 2024 年准备好文件且在 2025 发布了一些版本，则在程序的每个文件开头，添加如下的版权声明和许可证声明：

```
Copyright 2024, 2025 GrapeX1

本文件是 grape-x1 的一部分。

grape-x1 是自由软件：你可以再分发之和/或依照由自由软件基金会发布的 GNU 通用公共许可证修改之，无论是版本 3 许可证，还是（按你的决定）任何以后版都可以。

发布 grape-x1 是希望它能有用，但是并无保障;甚至连可销售和符合某个特定的目的都不保证。请参看 GNU 通用公共许可证，了解详情。

你应该随程序获得一份 GNU 通用公共许可证的复本。如果没有，请看 <https://www.gnu.org/licenses/>。
```

[为什么要有许可证声明？](https://www.gnu.org/licenses/gpl-howto.html#why-license-notices)

#### 许可证文件

你应该在程序中包含一份许可证的拷贝。所有程序，无论是 GPL，还是 LGPL，都应该包含 [GPL 的纯文本版](https://www.gnu.org/licenses/gpl.txt)。对 GNU 程序来说，我们的惯例是把许可证放在一个叫做 COPYING 的文件里。

如果你的程序按照 GNU AGPL 发布，那么请使用 [GNU AGPL 的纯文本版](https://www.gnu.org/licenses/agpl.txt)，而不是 GNU GPL 的纯文本版。

如果你的程序按照 Lesser GPL 发布，那么你还要包含一份 [LGPL 的纯文本版](https://www.gnu.org/licenses/lgpl.txt)，通常放在叫做 COPYING.LESSER 的文件里。请注意，LGPL 是在 GPL 基础上的一些额外授权，所以你的程序包含 LGPL 和 GPL 两个许可证拷贝非常关键，这样用户才能够全面了解他们的权利。

#### 联系方式

从实用的原因来看，在比如 README 文件里，包含你的联系方式是非常重要的，但是对实施许可证的法律问题来说，这个并不相关。

### GPLv3 的兼容性

使用 GNU GPLv3 作为开源许可证的作品仓库，能包含被其他许可证授权的作品吗？浏览 GNU 网页：[各类许可证及其评论](https://www.gnu.org/licenses/license-list.html)，以了解某个许可证是否兼容 GPL。

需要注意的是，如果将 GPLv3 代码与其他许可证（如 BSD 或 MIT）的代码结合成一个更大的程序，则整个程序必须遵循 GPLv3，除非这些独立功能的作品本身就不受 GPLv3 约束。

## 知识共享许可证

对于开源的文档、公开的博客等，常用的版权协议（版权许可）为知识共享（Creative Commons, CC）许可证。

CC 许可证选择器：[选择一个知识共享许可证](https://creativecommons.org/choose/)。

[Creative Commons Attribution 4.0 International（简称 CC BY 4.0）许可证](https://creativecommons.org/licenses/by/4.0/legalcode)，是一个非 [copyleft](https://www.gnu.org/licenses/copyleft.html) 的自由许可证，它适用于艺术和娱乐作品以及教育作品。它兼容 GNU GPL 的所有版本；不过，像全部 CC 许可证一样，[它不应该用于软件](https://creativecommons.org/faq/#can-i-apply-a-creative-commons-license-to-software)。

葡萄诚意的大部分文档，都将使用 CC BY 4.0 许可证。

## 参考

[（转）程序员都应该了解下版权和开源协议](https://blog.csdn.net/2401_84664550/article/details/141937932)

[如何正确使用知识共享（CC）协议？](https://m.bilibili.com/opus/821484161201078291)

[如何在你的软件中使用 GNU 许可证](https://www.gnu.org/licenses/gpl-howto.html)

[各类许可证及其评论](https://www.gnu.org/licenses/license-list.html)

[程序和软件的区别](https://metaso.cn/s/R9u8JPT)
