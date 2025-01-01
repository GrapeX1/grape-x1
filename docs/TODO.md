---
title: "待办事项"
author: GrapeX1
description: "未完成的任务。"
date: 2024-12-30
time: 21:21
---

## Example

{{date:YYYY-MM-DD}}

write a example for editing TODO.md file

## 自动生成目录

2024-12-30

根据 Markdown 文档的文件名和 properties——标题（title）、日期（date）、时间（time）、标签（tag）等，自动在[目录](docs/contents.md)文档生成内容。

以 grape-x1 仓库 docs 文件夹内的两个文档为例子。它们的文件名和 properties 分别如下所示。

[copyright-license.md](docs/copyright-license.md)：

```markdown
---
title: 版权协议
author: GrapeX1
description: 开放源代码和知识共享的版权协议，可以保护创作者。
date: 2024-12-29
time: 22:04
tags:
  - license
---
```

[document-style-guide.md](docs/document-style-guide.md)：

```markdown
---
title: "文档风格指南"
author: GrapeX1
description: "文档的写作规范。"
date: 2024-12-30
time: 16:41
tags:
  - guide
---
```

假设存在 grape-x1/docs/example.md 文件，其 properties 如下所示：

```markdown
---
title: "样例1"
author: GrapeX1
description: "为自动生成目录编写的样例，版本 1。"
date: 2024-12-30
time: 17:52
tags:
  - guide/example
---
```

则使用程序自动生成目录，输入以上 3 个文档，将输出以下内容：

```markdown
# 目录

## 指南

1. [文档风格指南](docs/document-style-guide.md) 2024-12-30 16:41

### 样例

1. [样例1](docs/example.md) 2024-12-30 17:52

## 许可证

1. [版权协议](docs/copyright-license.md) 2024-12-29 22:04

## 无标签

- 空

```

以上用标签作为标题，所以时间或标题首字母等将成为列表排序的依据。也可以考虑用时期和/或时间作为标题。
