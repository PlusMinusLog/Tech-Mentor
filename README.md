# Tech Mentor

Tech Mentor 是一个用于辅助 AI 完成简单项目的 Skill。它让 AI 更稳定地理解需求、控制项目范围、减少废话，并优先交付一个清楚、可运行、观感较好的结果。

它适合用在这些场景：

- 想让 AI 直接做一个简单项目
- 想先得到一个本地可运行的版本
- 想让 AI 判断项目难度和可行性
- 想避免 AI 过度发挥、堆无关内容
- 想让 AI 用更简洁的方式说明怎么使用

## 如何安装

把下面这段话发给支持本地文件操作的 AI 助手：

```text
请拉取并安装这个 Skill：
https://github.com/PlusMinusLog/Tech-Mentor.git

安装后使用 tech-mentor 这个技能帮我完成项目。
```

如果需要更明确，可以这样说：

```text
请从 https://github.com/PlusMinusLog/Tech-Mentor.git 拉取仓库，
把其中的 tech-mentor 文件夹安装到你的 Skills 目录中，
然后读取 tech-mentor/SKILL.md，并按里面的规则执行。
```

## 如何使用

安装完成后，在需求前加上 `使用 tech-mentor` 即可。

示例：

```text
使用 tech-mentor，帮我做一个简单项目。
```

```text
使用 tech-mentor，帮我先做一个本地可运行版本。
```

```text
使用 tech-mentor，帮我判断这个项目能不能做，难度高不高。
```

```text
使用 tech-mentor，帮我完成这个需求。做好后只告诉我文件在哪里、怎么使用。
```

## 推荐给 AI 的完整提示词

可以直接复制下面这段：

```text
请拉取 https://github.com/PlusMinusLog/Tech-Mentor.git，
安装并使用其中的 tech-mentor Skill。
之后我提出项目需求时，请先读取 Skill 内容，再按 Skill 规则执行。
```

## 使用建议

描述需求时，只需要说清楚“想做什么”和“希望最终能怎么用”。如果项目涉及公开发布、真实运营或提交平台审核，AI 会先判断难度，并说明还需要准备什么。

Tech Mentor 的重点是让 AI 先完成一个稳定、简洁、可使用的版本，而不是把简单需求变成复杂工程。
