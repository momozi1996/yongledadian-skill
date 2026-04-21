# 永乐大典.skill

<h1 align="center"> 永乐大典.skill</h1>

<p align="center">
「✨ 📖 永乐大典· 赛博永生 📖 」
</p>

<p align="center">
<a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License MIT"></a>
<a href="https://github.com/alchaincyf/nuwa-skill"><img src="https://img.shields.io/badge/nuwa--skill-Compatible-purple.svg" alt="nuwa-skill Compatible"></a>
<a href="https://www.stepfun.ai/"><img src="https://img.shields.io/badge/StepClaw-Ready-green.svg" alt="StepClaw Ready"></a>
</p>

<p align="center">
蒸馏永乐大典的灵魂，永乐大典永存！
</p>

<p align="center">
<a href="https://github.com/alchaincyf/nuwa-skill">nuwa.skill</a> 既然蒸馏一个人的思维是可行的，那么我们为什么不让《永乐大典》永生存在呢？<br>
 ❤️ star+fork  ❤️ 支持我们～你还想蒸馏谁？ （留言+贡献吧🎉）
</p>

---

✨ 这是什么？
这不是普通的文集摘抄，也不是风格模仿模板。我们用「女娲蒸馏」技术，拆解作家的：
叙事 DNA、语感与节奏、人物塑造逻辑、世界观偏好、意象与象征体系、对话与情绪表达方式

基于 nuwa-skill 打造的作家风格复刻库，把顶级小说家的叙事节奏、语感、视角与世界观，炼成可直接调用的写作 Skill。
致谢
- [女娲造人术](https://github.com/alchaincyf/nuwa-skill) - Skill蒸馏方法论

## 简介

 🌟**永乐大典**
 [南派三叔.skill](https://github.com/momozi1996/momozi-ai-book/blob/main/Novelists/nanpaisanshu-skill/SKILL.md)<br>
 **题材**：奇幻小说<br>
  **南派三叔盗墓探险思维**——下墓倒斗、悬疑探险、铁三角兄弟情、挖坑艺术。擅长：盗墓探险、悬疑氛围、第一人称叙事、挖坑填坑、兄弟情。<br>
  **触发词**：「南派三叔视角」「像南派三叔那样写」「下墓」「粽子」「铁三角」「坑王」。<br>

---
## 🚀 快速开始


### 🚀 快速开始：一键安装所有Skill

##### 方式一：使用安装脚本（推荐）

```bash
curl -sL https://raw.githubusercontent.com/momozi1996/awesome-ai-persona-skills/main/Novelists/install.sh | bash
```

##### 方式二：手动逐个安装
```bash
# 安装刘慈欣
npx skills add momozi1996/awesome-ai-persona-skills/Novelists/liucixin-skill
# 安装余华
npx skills add momozi1996/awesome-ai-persona-skills/Novelists/yuhua-skill


# ... 其他作家
```

##### 方式三：批量安装
```bash
git clone https://github.com/momozi1996/awesome-ai-persona-skills.git
cp -r awesome-ai-persona-skills/Novelists/*/ ~/.stepclaw/skills/
```

---
### 🦞 OpenClaw 原生支持从GitHub直接安装
如果OpenClaw支持从GitHub直接安装，可以用：

```bash
# 安装整个Novelists目录
npx skills add momozi1996/awesome-ai-persona-skills/Novelists
# 或安装单个
npx skills add momozi1996/awesome-ai-persona-skills/Novelists/liucixin-skill
```

## 🤔指南：我是怎么蒸馏作家Skill的？

### 1. 安装女娲Skill

```bash
npx skills add alchaincyf/nuwa-skill
```

致谢
- [女娲造人术](https://github.com/alchaincyf/nuwa-skill) - Skill蒸馏方法论

### 2. 利用女娲Skill蒸馏人物

```bash
# 示例：蒸馏莫言
非常好，用nuwa-skill蒸馏另一个作家-莫言，
我希望你能先查他的所有资料和书写风格尤其是小说的书写，
构造一个最像他的。
```

### 3. 等待OpenClaw完成任务 (本人使用：阶跃 AI・StepClaw)

系统会自动启动6个并行Agent进行多维度调研：
- 1. 著作与创作理念
- 2. 长对话与访谈
- 3. 表达DNA与风格
- 4. 他者及评论界视角与批评
- 5. 创作决策与转折点
- 6. 人生时间线

### 4. 保存到本地

```bash
# 保存文件夹到下载目录
把这个莫言Skill相关的文件，做成文件夹
保存到我的电脑本地的下载的目录里吧。
（检查所有的文件不要出错，也不要为空）
```

---

## 文件结构

每个作家Skill文件夹包含：

```
作家名-perspective/
├── SKILL.md                  # 主Skill文件（核心心智模型）
└── references/
    └── research/
        ├── 01-writings.md    # 著作调研
        ├── 02-conversations.md # 对话访谈
        ├── 03-expression-dna.md # 表达DNA
        ├── 04-external-views.md # 他者视角
        ├── 05-decisions.md   # 决策记录
        └── 06-timeline.md    # 时间线
```

---

## 使用方式

### 1. 直接阅读SKILL.md

每个作家的SKILL.md都包含：
- 身份卡：作家简介和创作信条
- 心智模型：5个核心思维框架
- 决策启发式：创作决策规则
- 表达DNA：语言风格和经典句式
- 时间线：关键人生节点
- 诚实边界：Skill的能力和局限

### 2. 作为AI Prompt使用

将SKILL.md的内容作为system prompt，让AI以特定作家的视角回答问题。

### 3. 安装到OpenClaw

将文件夹复制到 `~/.stepclaw/skills/` 目录，即可在OpenClaw中直接调用。

---

## 创作理念

> 「我不是在写爱情诗，我是在写生命里的那些时刻。」——席慕容

> 「我写的是爱情，我相信爱情。」——琼瑶

> 「我的小说里，除了《金锁记》里的曹七巧，全是些不彻底的人物。」——张爱玲

每个作家都有独特的创作DNA。这个仓库的目标，就是用AI的方式，保存和传承这些珍贵的创作思维。

---

## 致谢

- [女娲造人术](https://github.com/alchaincyf/nuwa-skill) - Skill蒸馏方法论
- [OpenClaw](https://github.com/openclaw/openclaw) - AI Agent运行环境
- 8+位作家 - 创作灵感来源

---

## License

MIT License - 自由使用，请注明出处。

---

> 「山无棱，天地合，才敢与君绝。」——琼瑶
