# ABC Listening Lab

这是一个长期英语听力训练项目。

这个仓库用于持续训练、复盘和追踪英语听力问题。材料主要来自 ABC Australia、ABC News 等真实英语内容，重点放在新闻英语、澳洲口音、连读弱读、复杂句理解、数字地名识别和高价值表达积累。

## 训练目标

- 提高真实新闻材料的听力理解能力
- 熟悉澳洲英语里的发音、节奏和常见表达
- 训练连读、弱读、省音和语速压缩的识别
- 提升人名、地名、数字、金额、百分比的快速反应
- 积累新闻英语和日常高频表达
- 用 shadowing 练习语音、节奏和断句
- 长期追踪反复听错、听漏、误判的地方

## 这个仓库怎么用

本地 ASR 识别出来的转写文件放在 `raw-transcripts/`。

如果有裸听记录，就放到 `my-listening-notes/`。这些记录很重要，因为它们能说明学习者真实听不清、听错或不确定的地方。

每次处理一份新材料时，会生成或更新：

- 整理后的学习转写
- 本次听力分析
- 长期词汇库
- 听力陷阱记录
- shadowing 跟读句子
- 复盘日志

## 目录结构

```text
raw-transcripts/
  本地 ASR 原始转写，格式可以是 .txt、.srt 或 .vtt。

my-listening-notes/
  裸听记录，比如没听清的词、猜错的句子、漏掉的数字。

transcripts/
  整理后的学习版转写，保留原文表达，并标注 ASR 可疑之处。

analysis/
  每次材料的详细听力分析，包括难句、听力陷阱、词汇和复盘问题。

vocab-bank/
  长期积累的高价值词汇和表达。

listening-traps/
  可能反复出现的听力问题和易错模式。

shadowing/
  适合跟读的句子，用来训练节奏、弱读、断句和表达。

review-log.md
  每次训练的总复盘，用来追踪长期问题和进步。
```

## 文件命名规则

```text
raw-transcripts/YYYY-MM-DD.txt
raw-transcripts/YYYY-MM-DD.srt
raw-transcripts/YYYY-MM-DD.vtt

my-listening-notes/YYYY-MM-DD_notes.md

transcripts/YYYY-MM-DD.md
analysis/YYYY-MM-DD_analysis.md
```

## 每次训练流程

1. 把新的 ASR 转写放进 `raw-transcripts/`。
2. 如果有裸听卡点，把记录放进 `my-listening-notes/`。
3. 根据 prompt 生成学习转写和听力分析。
4. 更新词汇库、听力陷阱、shadowing 句子和 review log。
5. 复习本次最重要的 3-5 个问题。
6. 下次训练时，检查这些问题有没有重复出现。

## 复盘重点

每次训练后，尽量回答这些问题：

- 到底哪里没听出来？
- 是词汇不认识，还是声音没识别出来？
- 是连读弱读问题，还是句子结构太长？
- 是背景知识不够，还是新闻表达不熟？
- 这个问题以前出现过吗？
- 哪些表达值得长期记？
- 哪些句子值得反复 shadowing？

## 重要提醒

如果某次没有裸听记录，分析只能说明“潜在听力难点”，不能直接判断那就是学习者真实听错的地方。

这个项目的核心不是整理漂亮笔记，而是长期追踪真实听力弱点，让每次训练都能比上一次更清楚地知道：卡在哪里，为什么卡住，下一次该怎么练。
