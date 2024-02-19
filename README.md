# 业务文档

## 仓库内容

这里包含了我所有主要负责功能的业务文档，文件结构为:

```json
|- latex // latex 的统一样式文件
|- Private // 标准包需求 
    |- Doc1
        |- Doc1.tex // latex 入口文件
        |- Doc1.pdf // 编译后的 pdf 文件
        |- contents // 每小节内容
        |- figures // tikz 图片
|- Web  // 公有云需求
    |- Doc2
```

已有的业务文档包括:

|需求|文件夹|类型|
|--|--|--|
|Ukey变更|UkeyChange|标准包需求|

## 书写与提交规范

全部使用 latex 与 tikz 编写，每次文档更新提交一次 pdf 文件。

### commit 规范

因为是自己的项目，所以不采用公司的提交规范，我的 commit message 格式为: emoji [文档名:] message，例如:
- 🔖 UkeyChange: 首次提交ukey变更文档
- 🐛 UkeyChange: 修复xxx处业务漏洞
- 🔧 更新latex样式文档

采用的 git emoji 包括:
|emoji|文本|含义|
|--|--|--|
|🔖|:bookmark:|首次发布业务文档|
|📑|:pencil:|更新已有业务文档|
|🐛|:bug:|修复业务文档的问题|
|🔧|:wrench:|更新配置文件(一般为latex配置)|

### latex 编译

应该没啥人用 latex 了，这里留一个 texlive+vscode 编译 latex 文档的教程链接: [知乎](https://zhuanlan.zhihu.com/p/624932249)

或者直接联系本人，如果离职了请 QQ 联系我: 673486387