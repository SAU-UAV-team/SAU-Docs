# Cerebrum Git 协作规范

## 基本原则

- `main` 是大家共同使用的正式版本。
- 平时不要直接在 `main` 上修改。
- 每个人在自己的分支上工作，完成后通过 Pull Request 合并。
- 一篇论文尽量对应一个 Markdown 文件，减少互相冲突。

## 开始一次新工作

1. 先在 Obsidian Git 中 Pull 最新内容。
2. 从最新的 `main` 创建新分支。
3. 分支名称建议使用：

   ```text
   姓名/论文简称
   ```

   例如：

   ```text
   zhangsan/mappo-paper
   ```

4. 确认 Obsidian 底部显示的是自己的分支，再开始编辑。

也可以在 Obsidian 中按 `Ctrl + P`，搜索 `Create new branch` 创建分支。

## 完成一次工作

1. 检查论文链接、方法和结果。
2. 在 Obsidian Git 中执行 `Commit all changes`。
3. 提交说明写清楚，例如：

   ```text
   新增：MAPPO 论文笔记
   ```

4. Push 自己的分支。
5. 在 GitHub 上创建 Pull Request，目标分支选择 `main`。
6. 请一位同学快速检查后合并。

## 开始下一次工作

合并完成后：


1. 切换回 `main`。
2. Pull 最新内容。
3. 再创建新的工作分支。

## 遇到冲突怎么办

不要强行覆盖别人的修改。先停止 Push，把冲突文件和情况发到组内讨论，确认后再处理。

每个人使用自己的 GitHub 账号和 SSH 密钥，不要共享账号或私钥。

