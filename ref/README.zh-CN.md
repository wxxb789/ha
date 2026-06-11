# ref — 外部参考

> [English](./README.md) · **简体中文**

一份精选的 agent / skill / harness 仓库地图，值得借鉴学习。这里**不 vendor
代码**——只是我寻找灵感、可借鉴模式的去处。某个参考被验证有用后，就把它吸收进
对应的顶层目录——[`../skills/`](../skills/)、[`../orchestration/`](../orchestration/)、[`../agents/`](../agents/) …（保留署名）。

## 如何添加

在下表追加一行。**“可借鉴什么”要具体**——点名那个具体的想法、模式或文件，
而不是笼统的“好仓库”。

| 仓库 | 类别 | 可借鉴什么 | 链接 |
|---|---|---|---|
| _(示例)_ VoltAgent/awesome-agent-skills | skills 索引 | 可供挖掘 skill 灵感的精选目录 | <https://github.com/VoltAgent/awesome-agent-skills> |
| _(示例)_ kepano/obsidian-skills | skills | 干净的 `SKILL.md` 写法 | <https://github.com/kepano/obsidian-skills> |

> 标 _(示例)_ 的行是起步样例——替换成你自己的精选。

## 可选：vendor 代码

若想把某个参考的代码放到本地，用 git submodule 加到 `ref/<name>/` 下。优先用
链接——submodule 会撑大仓库、拖进别人的历史。绝不复制带 secret 或个人路径的
代码。
