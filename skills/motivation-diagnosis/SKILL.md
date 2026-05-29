---
name: motivation-diagnosis
description: |
  Use when a user asks why people do not start, continue, finish, return to, or stop a behavior; or when a workflow, habit, product, training, community, course, or agent process has weak motivation. Do not use for pure usability, technical failure, or missing-capability issues unless motivation is also part of the problem.
source_book: 《遊戲化實戰全書》 周郁凱 Yu-kai Chou
source_chapter: ch.3, ch.16; Section I
tags: [motivation, diagnosis, behavior-design, octalysis]
related_skills:
  - slug: strategy-dashboard
    relation: depends-on
  - slug: core-drive-intervention
    relation: composes-with
  - slug: motivation-ethics-review
    relation: composes-with
---

# Motivation Diagnosis

## R — 原文 (Reading)

> "沒有八項核心動力的任何一項，就代表缺乏動機。"
>
> — 《遊戲化實戰全書》ch.3

## I — 方法論骨架 (Interpretation)

Motivation diagnosis converts a vague behavior problem into a map of current, missing, overused, and misused drives.

The key move is to stop asking "what game mechanic should we add?" and start asking "what reason does this actor currently have to act?"

Diagnose one concrete target behavior at a time. A person may have strong motivation to sign up but weak motivation to return, contribute, finish, or advocate.

Use CD1-CD8 as diagnostic categories, then check left/right, white/black, and journey stage. A behavior may be active for the wrong reason, such as CD8 fear or CD6 urgency, while missing CD1 meaning or CD3 autonomy.

The output is not a solution yet. It is a defensible explanation of why the behavior happens, does not happen, stops, or becomes unhealthy.

## A1 — 書中的應用 (Past Application)

### 案例 1: LinkedIn

- **問題**: Users had reason to create a professional profile but less reason to keep engaging.
- **方法論的使用**: The framework identifies strong left-brain, external career value but weaker right-brain intrinsic activity.
- **結論**: Add social and creative participation, not just more profile completion.
- **結果**: The source uses LinkedIn as a diagnosis example for motivation imbalance.

### 案例 2: Waze

- **問題**: A navigation utility could be replaced by other maps.
- **方法論的使用**: Analyze the journey across CD1 community mission, CD3 reporting, CD4 personalization, CD5 thanks, CD7 road uncertainty.
- **結論**: Waze is sticky not only because of utility, but because users help repair a shared traffic world.
- **結果**: The source presents Waze as a multi-drive, multi-stage example.

## A2 — 觸發場景 (Future Trigger)

### 用户會在什麼情境下需要這個 skill?

1. A behavior has weak adoption, completion, retention, contribution, or advocacy.
2. A habit or workflow starts well but fades.
3. A product or learning flow has signups but poor repeat behavior.
4. Users are acting, but only through pressure, rewards, or fear.
5. A team wants to understand "why people don't do this" before designing.

### 語言信號

- "為什麼大家不做/做不久/停不下來?"
- "這個流程很合理，但沒人用。"
- "我們要不要加徽章/排行榜/獎勵?"
- "使用者註冊了但不回來。"
- "我想診斷這個習慣/工作流/課程/agent queue 的動機問題。"

### 與相鄰 skill 的區分

- Use `strategy-dashboard` when the main need is to define metrics, actors, target behaviors, and design brief.
- Use `core-drive-intervention` after diagnosis, when the user asks what to change.
- Use `motivation-ethics-review` when the proposed design already uses pressure, scarcity, randomness, loss, or social manipulation.

## E — 可執行步驟 (Execution)

1. **Frame the behavior**
   - Define actor, target behavior, context, stage, and success metric.
   - Completion standard: the behavior is concrete enough to observe.

2. **Map current drives**
   - For CD1-CD8, mark each as strong, weak, missing, overused, or misused.
   - Completion standard: every drive has a one-sentence evidence note.

3. **Check motivation shape**
   - Classify the current design as left/right, white/black, implicit/explicit, and stage-specific.
   - Completion standard: identify whether motivation is durable, transactional, urgent, social, or fragile.

4. **Explain the failure or risk**
   - Name the primary missing drive, overused drive, and drop-off point.
   - Completion standard: output a concise diagnosis that explains the observed behavior.

5. **Hand off to design**
   - Recommend which next skill should run: `strategy-dashboard`, `core-drive-intervention`, `journey-stage-mapping`, or `motivation-ethics-review`.
   - Completion standard: no mechanics are proposed unless the diagnosis is complete.

## B — 邊界 (Boundary)

### 不要在以下情況使用此 skill

- The problem is purely technical, such as a broken button, missing permission, or unavailable data.
- The actor lacks real ability, access, money, time, safety, or trust; solve those before motivation design.
- The user asks for clinical diagnosis, therapy, addiction treatment, or medical/mental-health advice.

### 作者在書中警告的失敗模式

- Treating points, badges, and leaderboards as motivation itself.
- Using a framework as a checklist without empathetic, context-specific answers.
- Letting black-hat drivers create engagement that users feel relieved to escape.

### 作者的盲點 / 時代局限

- Many source cases are product and business oriented; when diagnosing personal, educational, health, or AI-agent workflows, translate metrics and actors carefully.
- Case metrics may be historical and should not be treated as current market evidence.

### 容易混淆的鄰近方法論

- Friction analysis: asks "what makes the action hard?"
- Motivation diagnosis: asks "why would the actor want to act at all?"

## 相關 skills

- depends-on: `strategy-dashboard` when the success metric or target behavior is unclear.
- composes-with: `core-drive-intervention` for solution design.
- composes-with: `motivation-ethics-review` when pressure, loss, scarcity, or randomness appears.

## 審計信息

- **驗證通過**: V1 ✓ / V2 ✓ / V3 ✓
- **測試通過率**: 100% (see `test-results.md`)
- **蒸餾時間**: 2026-05-29
