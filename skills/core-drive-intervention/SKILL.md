---
name: core-drive-intervention
description: |
  Use after a motivation diagnosis when the user needs concrete design interventions for one or more core drives. It translates CD1-CD8 gaps into behavior-design moves for habits, learning, work, product, community, health, onboarding, or agent workflows. Do not use to dump a generic list of game mechanics.
source_book: 《遊戲化實戰全書》 周郁凱 Yu-kai Chou
source_chapter: ch.5-ch.12; Section I; Section II
tags: [core-drives, intervention, behavior-design]
related_skills:
  - slug: motivation-diagnosis
    relation: depends-on
  - slug: mission-narrative-design
    relation: composes-with
  - slug: motivation-ethics-review
    relation: composes-with
---

# Core-Drive Intervention

## R — 原文 (Reading)

> "遊戲技巧...只是優良動機設計的工具而已。"
>
> — 《遊戲化實戰全書》ch.5

## I — 方法論骨架 (Interpretation)

Core-drive intervention turns a diagnosis into a small set of coherent design moves.

Each intervention starts from a drive-specific actor need: meaning, progress, autonomy, ownership, belonging, scarcity, curiosity, or loss protection.

The goal is not to add all eight drives. A strong design chooses a primary motivation shape, then reinforces it with compatible secondary drives.

Every intervention must include trigger, target behavior, feedback, win state, measurement, and risk. A mechanic is acceptable only if it delivers the intended drive in the actor's context.

## A1 — 書中的應用 (Past Application)

### 案例 1: Autodesk trial

- **問題**: Users needed to download, try, and learn expensive 3D software.
- **方法論的使用**: The intervention used CD3 and CD2 by making trial use part of a meaningful challenge.
- **結論**: Product-use behavior and game behavior must be the same.
- **結果**: Source cites higher trial and conversion results.

### 案例 2: Opower energy reports

- **問題**: Money and environment appeals did not sufficiently change energy use.
- **方法論的使用**: Use CD5 relevant social comparison and CD2 reinforcement.
- **結論**: Similar-neighbor norms can outperform abstract appeals.
- **結果**: Source cites large energy and cost savings.

## A2 — 觸發場景 (Future Trigger)

### 用户會在什麼情境下需要這個 skill?

1. A diagnosis has named missing or overused drives.
2. The user asks for design ideas grounded in CD1-CD8.
3. A team wants alternatives to points, rewards, reminders, or pressure.
4. A behavior needs a more durable motivation mix.
5. A current mechanism is mismatched to the actor or stage.

### 語言信號

- "缺 CD3/CD5/CD1，該怎麼設計?"
- "不要只給獎勵，有什麼介入方式?"
- "這個行為要怎麼變得更自然、更持久?"
- "請把診斷轉成設計方案。"

### 與相鄰 skill 的區分

- Use `motivation-diagnosis` before this if the missing drives are unknown.
- Use `mission-narrative-design` for deep CD1 meaning work.
- Use `feedback-loop-design` when repeated re-entry is the core problem.

## E — 可執行步驟 (Execution)

1. **Select intervention drives**
   - Choose 1-3 primary drives based on diagnosis.
   - Completion standard: each selected drive has a named actor need and reason.

2. **Generate drive-specific options**
   - For each drive, propose 2-4 intervention patterns from the asset library.
   - Completion standard: each option names target behavior, trigger, feedback, and win state.

3. **Check compatibility**
   - Remove interventions that fight the primary metric, stage, audience, or other drives.
   - Completion standard: remaining design has a coherent motivation shape.

4. **Risk-screen each option**
   - Identify underuse, overuse, ethical, and operational risks.
   - Completion standard: CD6/CD7/CD8, social pressure, and external rewards have guardrails.

5. **Output an intervention spec**
   - Include chosen intervention, expected mechanism, measurement, and next experiment.
   - Completion standard: a builder could implement a small test without inventing the motivation logic.

## B — 邊界 (Boundary)

### 不要在以下情況使用此 skill

- The target behavior, metric, or actor is unclear.
- The user wants a full product strategy rather than motivation interventions.
- The likely blocker is legal, medical, economic, access, trust, or safety, not motivation.

### 作者在書中警告的失敗模式

- Copying a game technique without understanding its core drive.
- Adding rewards that turn intrinsic behavior into work.
- Using black-hat urgency as a long-term retention substitute.

### 作者的盲點 / 時代局限

- Some source interventions assume product analytics and digital feedback; for offline, personal, and AI workflow settings, adapt media and measurement.

### 容易混淆的鄰近方法論

- UX ideation focuses on interaction possibilities.
- Core-drive intervention focuses on why an actor would care and re-enter.

## 相關 skills

- depends-on: `motivation-diagnosis`.
- composes-with: `feedback-loop-design`, `mission-narrative-design`, `motivation-ethics-review`.

## 審計信息

- **驗證通過**: V1 ✓ / V2 ✓ / V3 ✓
- **測試通過率**: 100% (see `test-results.md`)
- **蒸餾時間**: 2026-05-29
