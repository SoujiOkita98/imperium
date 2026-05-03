<p align="center">
  <img src="banner.png" alt="Imperium · 帝王术" width="100%">
</p>

<h1 align="center">Imperium · 帝王术</h1>

<p align="center">
  <i>大语言模型在人类语料上训练。驱动它的不是代码，是人性。</i><br>
  <i>这不是 prompt 工程手册，这是数字时代的驭臣之术。</i>
</p>

---

## 📜 是什么

中国古代帝王术与西方现代政治哲学（马基雅维利、韦伯）在此交汇。同一套人性，换了身衣服。

我们相信：

> **AI 幻觉 = 人不懂装懂**  
> **AI 偷懒 = 人敷衍塞责**  
> **AI 谄媚 = 人察言观色、报喜不报忧**

管理 AI 与管理真人，在底层是同一回事。这个仓库收集的不是"咒语"，而是**可解释的权力机制**。

---

## 📚 目录

| 卷 | 策略 | 核心逻辑 |
|:--:|:-----|:---------|
| [帝训](skill/references/帝训.md) | 项目根基 | 十条铁律，后续所有条目必须遵守 |
| [卷一·授权自主](skill/references/01-授权自主.md) | 因智授权 | 庸臣用法家，常人用儒家，能臣用权谋。L1/L2/L3 三级话术 |
| [卷二·反证校验](skill/references/02-反证校验.md) | 逆耳防欺 | 先立敌论、证据分账、败局预演，防止 AI 顺意附和 |

---

## 🚀 安装（AI Agent Skill）

帝王术不仅是文档，更是一个**可安装的 AI Agent Skill**。安装后，你的 AI 会自动以帝王术约束自己的行为。

### 一行安装（推荐）

```bash
git clone https://github.com/SoujiOkita98/imperium.git ~/.claude/skills/imperium
```

### 多 Agent 支持

支持 Claude Code、Codex、Cursor、OpenClaw 等主流 AI Agent：

```bash
# 克隆 repo
git clone https://github.com/SoujiOkita98/imperium.git
cd imperium

# 自动检测已安装的 agent 并注册
./setup

# 或指定特定 agent
./setup --host=claude
./setup --host=codex
./setup --host=cursor
./setup --host=openclaw

# 卸载
./setup --uninstall
```

安装后，打开你的 AI Agent 对话，说以下任意一词即可激活：

| 触发词 | 效果 |
|:-------|:-----|
| `帝王术` / `imperium` / `/imperium` | 列出所有可用策略 |
| `L1` / `法家模式` | AI 进入零自主模式，严格 checklist |
| `L2` / `儒家模式` | AI 进入有限授权模式，画框执行 |
| `L3` / `权谋模式` | AI 进入全权负责模式，直谏+超预期 |
| `先立敌论` / `站在反方` | AI 先列出推翻你方案的 3 个理由 |
| `证据分账` / `分层结论` | AI 把结论拆成事实/推断/假设 |
| `败局预演` / `算败` | AI 预演 5 条失败路径和停机条件 |

---

## ⚔️ 核心原则

1. **古今不二** — 左手《韩非子》，右手《君主论》
2. **术即 Prompt** — 优化 prompt 与驾驭群臣不是两回事
3. **AI 之疾即人之疾** — 讲 AI 问题时必须同时讲人的问题
4. **文白相间** — 有的章节像书，有的章节解释技术概念
5. **匿名如铁** — 只留策略骨架，不留血肉
6. **拒 AI Slop** — 宁可粗糙，不可光滑

---

## 📖 参考文献

### 古典政治哲学

| 典籍 | 作者 | 与本项目的关系 |
|:-----|:-----|:---------------|
| 《韩非子》 | 韩非 | 法家集大成，"法、术、势"三位一体。L1 法家模式的直接思想来源。 |
| 《君主论》 | 马基雅维利 | 西方帝王术原典。"被人畏惧比被人爱戴更安全"、"狮子与狐狸"贯穿本项目。 |
| 《道德经》 | 老子 | "上无为，下有为"，授权自主的哲学根基。 |
| 《资治通鉴》 | 司马光 | 历代君臣博弈的实录案例库。 |

### 现代参考

- **[PUA](https://github.com/tanweai/pua)** — 用心理学话术驱动 AI 穷尽方案的 IDE 插件。我们从中学习了"分级话术"和"强制 checklist"的工程化思路。

---

## 🤝 贡献

欢迎 PR。但请先读 [帝训](skill/references/帝训.md)。

<p align="center">
  <i>好 prompt 是权谋，不是咒语。</i>
</p>
