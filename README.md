# Markdown Extension Pack

## 简介

[![VSCode Plugin](https://vsmarketplacebadge.apphb.com/version-short/rxliuli.markdown-extension-pack.svg)](https://marketplace.visualstudio.com/items?itemName=rxliuli.markdown-extension-pack) [![GitHub ISSUES](https://img.shields.io/github/issues/rxliuli/markdown-extension-pack.svg)](https://github.com/rxliuli/markdown-extension-pack/issues)

这是一个 Markdown 扩展的扩展包，致力于为 VSCode 提供开箱即用的 Markdown 编辑环境。

## 插件列表

- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one): Markdown 编辑增强
- [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf): Markdown PDF 导出
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint): Markdown Linter
- [Local History](https://marketplace.visualstudio.com/items?itemName=xyz.local-history): 本地历史记录

## 功能

感谢 VSCode 及以上插件提供了一些功能让我们能够更好的在 VSCode 中进行 Markdown 写作，下面稍微介绍一下为什么这四个插件对于 VSCode Markdown 写作必不可少！

### Markdown All in One

为 VSCode 增强了 Markdown 支持

- 列表项回车自动追加，回车自动删除并变更序号（有序列表的话）
- 快速将文字加粗，变为斜体
- 选中文字并粘贴一个 URL 会自动转换为 Markdown URL
- 表格自动格式化对齐
- 生成文章标题

### Markdown PDF

允许将 Markdown 文档导出为 PDF 文档。众所周知 PDF 是相当流行的一种电子书籍格式，而且非常通用（所有的现代浏览器都直接直接打开 PDF 文档），所以它能够帮助与他人分享自己的文章。
甚至于，你可以用 Markdown 书写简历，然后导出为 PDF！

### markdownlint

和前端圈子中流行的 Linter 工具一样，它是为了规范 Markdown 的书写而存在的。它会强制让人遵循规范写 Markdown 文档，以帮助后来阅读/编辑这篇 Markdown 的人。

- 强制标题上下必须是空行
- 强制代码块必须声明语言
- 强制链接必须包含 URL
- 还有更多。。。

### Local History

这不是一个 Markdown 扩展，但对于写作却有着非同寻常的意义 -- 能够记录自己的写作历史，避免因为突发意外而丢失写作内容（来自吾辈所遇到的血淋淋的教训。。。）。它会在项目目录下生成一个 `.history` 文件夹，里面存放着所有使用 Markdown 编辑过的文件的历史记录，你可以将文件内容与历史记录对比并回退到任意记录。
