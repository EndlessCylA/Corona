# Corona（日冕）

一部长篇小说，设定于 2666 年。三人共创。

仓库本体是一个 [Obsidian](https://obsidian.md) 库——全部内容以 Markdown 笔记存放。

## 当前状态

- 创作进行中：设定与文稿在逐步整理、补齐
- 主仓 `main` 分支为最新版

## 库里的东西

| 文件 | 说明 |
| --- | --- |
| `IDEA.md` | 灵感速记 |
| `设定.md` | 世界观与设定集 |

之后会增加更多条目，尽量一页一个主题。

## 怎么参与

本库用 fork 协作：每个人在自己的副本里创作，改动以 Pull Request 汇总回主仓。

### 0. 准备

- 只读浏览：什么都不用装，在 GitHub 网页上看即可
- 想动笔：需要 [Git](https://git-scm.com/) 与 [Obsidian](https://obsidian.md/)（免费）

### 1. Fork

点本页右上角的 **Fork**，得到你自己的副本：`https://github.com/<你的用户名>/Corona`

### 2. 克隆到本地

```bash
git clone https://github.com/<你的用户名>/Corona.git
cd Corona
```

### 3. 用 Obsidian 打开

Obsidian →「打开文件夹作为库」→ 选择刚才克隆的 `Corona` 文件夹。

### 4. 关联主仓（一次即可）

```bash
git remote add upstream https://github.com/Madokana127/Corona.git
```

### 5. 日常写作

在 Obsidian 里正常写，写完提交：

```bash
git add -A
git commit -m "改动说明"
git push
```

### 6. 同步大家的更新

```bash
git pull upstream main
git push
```

### 7. 把改动交回主仓

在 GitHub 上，从你的 fork 发起 **Pull Request** 到主仓 `main` 分支。

没做过的话，见 [GitHub 官方文档：Fork（分叉）与同步](https://docs.github.com/zh/pull-requests/how-tos/work-with-forks/fork-a-repo)。

> 不想敲命令行：在 Obsidian 中安装社区插件 **Git**（[Vinzent03/obsidian-git](https://github.com/Vinzent03/obsidian-git)），Pull / Push 都能在界面里完成。

## 约定

- 用 Markdown 写，中文文件名没问题
- `.obsidian/workspace.json`（界面布局）是个人的本地状态，不入库，不用管
- 提交信息写清楚「改了什么」即可，不讲究格式
- 移动或重命名文件前先说一声——Obsidian 的 `[[双链]]` 跟着文件名走，改名会让链接断开

## 常见问题

**不想装环境，只想改一点？**

小改动可以直接在 GitHub 网页上编辑文件并提交。

## 联系

- 主理人：[@Madokana127](https://github.com/Madokana127)
- 共创伙伴：[@EndlessCylA](https://github.com/EndlessCylA)<!-- 另一位在这里追加 -->
- 有想法或疑问：[Issues](https://github.com/Madokana127/Corona/issues) 或直接找我们

---

本仓库内容为三人共创作品，未经允许请勿转载或引用。
