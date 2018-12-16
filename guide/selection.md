# 选题步骤

选题通常由固定的人员担任，其采用我们开源贡献的[选题工具](https://github.com/LCTT/lctt-scripts)对选定的原文进行采集、转换和整理，最终形成符合规范的待翻译原文。

原文会通过 PR [^1] 的方式发送到 LCTT [TranslateProject 项目仓库](https://github.com/LCTT/TranslateProject)上。通过 CI [^2] 检查和人工审核后，会正式进入仓库。

非专职选题也可以参与选题工作，有两种方式：

- 采用上述选题工具，自行对青睐的文章（需要符合 LCTT 选题标准）制作待译原文，并 PR 到项目仓库，由管理员进行审查和合并
- 以 [issue](https://github.com/LCTT/TranslateProject/issues) 的方式提交到项目仓库，由专职选题参考是否可以纳入

## 选题标准

我们的选题范畴包括：

- 开源相关的技术文章，包括操作系统、软件开发、系统运维等等
- 开源相关的评论性文章
- 开源相关的资源介绍文章
- 开源相关的重大新闻文章

我们所选题的文章需要满足如下条件：

- 公开领域的文章
- CC-BY-NC 的文章
- 明确书面授权的文章

我们倾向的选题可以是入门类、进阶类的文章，也可以是专业类的文章，但是不收录：

- 过于冷僻的文章
- 内容组织混乱的文章
- 内容明显错误和自相矛盾的文章
- 违反中国法律法规和公序良俗的文章
- 时间太久远的文章。
- 已经存在较好的译文。

## 选题模板

我们的选题模板经过了多次迭代修改，当前的选题模板为包含了元信息的[模板](topic_tmpl.txt)。

大家可以手工根据选题模板来将原文制作成选题文章，也可以采用上述工具来完成，并在检查生成的内容后提交选题 PR。

如果发现工具生成的文章和模板不匹配，请联系管理员和开发者。

## 选题源

当前的选题采集来源：

- 待列出。

大家也可以根据上述的选题标准来[建议](https://github.com/LCTT/TranslateProject/issues/9476)新的、稳定的选题源。

[^1]: PR，即<ruby>拉取请求<rt>Pull Request</rt></ruby>，是GitHub 的协作模式。
[^2]: CI，即<ruby>持续集成<rt>Continuous integration</rt></ruby>，是一种自动对代码进行检查和构建的机制，我们用来做合规性检查