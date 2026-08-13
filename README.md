# liwenya.skill —— 它是一个人民的 Skill 吗？！

> 这个 `liwenya.skill`，它正确吗？！  
> 它是不是一个人民的 Skill？！
>
> 一个 Skill，如果只会在句子后面加“恶不恶”“走着瞧”，它就掌握文亚精神了吗？！我看没有！
>
> 真正的文亚体，不是几个口号的问题。它有自己的世界观，有自己的判断路线，有自己的阵营变化，还有自己的历史规律！所以我们这个项目，不是简单模仿几句话，是要把**产生这些话的那台机器**研究清楚。
>
> 不信，你装上试试。咱们就走着瞧！

A parody/style skill for generating **文亚体 / 文亚宇宙** dialogue and narration.

> **Parody notice:** generated text is not an authentic Li Wenya quotation unless separately verified from a recording or reliable transcript.

## 文亚 Kernel

The core idea is simple:

> **Do not imitate the words. Simulate the machine that produces the words.**

```text
朴素直觉是底层真理
        ↓
先判断，再解释
        ↓
理论分歧变成路线分歧
        ↓
人和机构按当前立场重新分类
        ↓
网友的新设定自动进入世界观
        ↓
小事件被制度化、国际化、历史化
        ↓
历史最终会作出判断
```

In other words:

**文亚精神 = 朴素机械直觉 + 先定性后论证 + 立场条件化可信度 + 新旧路线斗争 + 网友输入自动入典 + 官僚化宇宙扩张 + 历史必然性。**

If the output merely sounds angry, the skill has failed.

## Quick start

一个 Skill，你不调用，你怎么知道它正确不正确？！

Load [`SKILL.md`](./SKILL.md), then give it a harmless topic or fictional premise:

```text
Use liwenya.skill in speech mode:
LLVM 把我的程序优化坏了。
```

```text
Use liwenya.skill in minke-tv mode:
月球土豆科学院突然改口支持另一套薯条理论。
```

## Four output modes

| Mode | What it generates |
|---|---|
| `speech` | 第一人称、面对镜头式文亚发言 |
| `minke-tv` | “重磅 / 光速变脸 / 波澜又起”式民科TV标题与旁白 |
| `conference` | 一本正经的第 N 次理论讨论大会 / 公报 |
| `wiki` | 把荒诞设定当既成历史写成世界观条目 |

Intensity can range from **本人语感 → 批斗体 → 文亚宇宙 → 鬼畜**.

## The important part: belief updates

A 文亚宇宙 character is not just a bag of catchphrases. New information changes the **classification of the source** before it changes the core theory.

```text
支持当前判断
→ 有识之士 / 正义力量

反对当前判断
→ 没搞清楚 / 受旧理论影响

昨天支持、今天反对
→ 光速变脸 / 重新归类

昨天反对、今天支持
→ 欢迎改正 / 重新吸收
```

The same institution can therefore be praised in one episode and questioned in the next. That is not necessarily a continuity bug; in 文亚宇宙 it is often the plot engine.

## Universe compiler

Any harmless meme premise can be expanded with four passes:

```text
普通事件
→ 学术化
→ 机构化
→ 国际化
→ 连续剧化
```

For example:

```text
网友说土豆应该切粗一点
→ 土豆动力学教授发表观点
→ 月球土豆研究所发布声明
→ 海外薯条学者加入讨论
→ 第十九次薯条理论讨论大会召开
```

This scale inflation is intentional.

## Repository layout

```text
.
├── SKILL.md
├── README.md
├── LICENSE
├── CONTRIBUTING.md
└── examples/
    ├── basic.md
    └── golden-tests.md
```

- [`SKILL.md`](./SKILL.md): the Wenya Kernel and generation VM.
- [`examples/basic.md`](./examples/basic.md): simple parody examples.
- [`examples/golden-tests.md`](./examples/golden-tests.md): regression examples for all output modes.
- [`CONTRIBUTING.md`](./CONTRIBUTING.md): contribution rules.

## Golden-test philosophy

When changing the skill, run the same premise through multiple modes and check that:

1. the outputs are recognizably from the same universe;
2. they are not merely copies with different formatting;
3. belief-update and faction logic still work;
4. the speaker does not become generic angry prose;
5. vocalizations and catchphrases remain sparse;
6. parody is never presented as an authentic quotation.

## Authenticity

Keep these categories separate:

1. verified recording;
2. reliable transcription;
3. uploader title / paraphrase;
4. community lore;
5. newly generated parody.

If someone asks “李文亚真的说过吗？”, leave roleplay mode and verify the source.

## Disclaimer

This repository is unaffiliated with Li Wenya. It is intended for parody, meme generation, and rhetorical/style study. Extreme fictional plots should stay obviously fictional; generated accusations should not be presented as factual claims about real people.
