---
name: strategy-dashboard
description: |
  Use before designing a motivation system when the goal, success metric, actor, target behavior, feedback channel, reward, or tradeoff is unclear. Especially useful for products, habits, learning, work, communities, health behavior, onboarding, and AI-agent workflows. Do not use as a generic project plan when motivation is irrelevant.
source_book: 《遊戲化實戰全書》 周郁凱 Yu-kai Chou
source_chapter: ch.17; Section III 3.1-3.4
tags: [strategy, behavior-design, metrics, intake]
related_skills:
  - slug: motivation-diagnosis
    relation: depends-on
  - slug: journey-stage-mapping
    relation: composes-with
  - slug: feedback-loop-design
    relation: composes-with
---

# Strategy Dashboard

## R — 原文 (Reading)

> "每項遊戲化計畫開始之初，我的第一步是界定以下五個項目。"
>
> — 《遊戲化實戰全書》ch.17

## I — 方法論骨架 (Interpretation)

The strategy dashboard is the minimum viable design brief for motivation work.

It prevents premature mechanics by forcing the designer to define ranked outcomes, motivated actors, target behaviors, feedback media, and rewards before ideation.

Its most important discipline is metric priority. A design cannot optimize every outcome equally; the primary success metric changes calls to action, triggers, feedback, and acceptable tradeoffs.

For a universal pack, "business metric" becomes success metric. The same dashboard can define a personal habit, course, employee workflow, community, onboarding flow, health behavior, or AI research process.

## A1 — 書中的應用 (Past Application)

### 案例 1: YukaiChou.com redesign

- **問題**: The site had multiple possible goals: subscribers, book sales, workshops, consulting, email, sharing, and video views.
- **方法論的使用**: The author ranked metrics, then listed users, desired actions, feedback media, and rewards.
- **結論**: Design starts from prioritized outcomes, not from available mechanics.
- **結果**: The source uses this as the full from-zero design example.

### 案例 2: Login vs signup interfaces

- **問題**: Interfaces differ depending on whether new-user signup or existing-user login is the primary metric.
- **方法論的使用**: Compare Facebook/Pinterest-style signup priority with PayPal/Amazon-style returning-user priority.
- **結論**: Metric priority changes visual hierarchy and target behavior.
- **結果**: Demonstrates why teams must rank success metrics before interface design.

## A2 — 觸發場景 (Future Trigger)

### 用户會在什麼情境下需要這個 skill?

1. The user wants to design or redesign motivation but goals are broad.
2. Stakeholders want multiple outcomes and no priority.
3. A project is about to add rewards, loops, or nudges without a behavior brief.
4. A workflow needs a clear target behavior and win state.
5. A team wants reusable design requirements before ideation.

### 語言信號

- "我們想提升參與/留存/完成率，但還沒想清楚。"
- "這個行為設計要從哪裡開始?"
- "我們有很多指標都想提升。"
- "幫我把這個需求轉成動機設計 brief。"
- "先不要想玩法，先定義架構。"

### 與相鄰 skill 的區分

- Use `motivation-diagnosis` when behavior failure is already observed and needs explanation.
- Use `journey-stage-mapping` when stages and drop-off points are the main issue.
- Use `feedback-loop-design` when repeated behavior and re-entry are already defined.

## E — 可執行步驟 (Execution)

1. **Rank success metrics**
   - List desired outcomes and sort them by priority.
   - Completion standard: one primary metric is named, with secondary metrics as inputs or constraints.

2. **Define motivated actors**
   - Identify actor groups and motivation segments.
   - Completion standard: each actor has a role, current state, and reason to care or not care.

3. **Define target behavior path**
   - List the concrete actions that lead to the success metric.
   - Completion standard: each action is observable and stage-labeled.

4. **Define feedback mechanisms and media**
   - Specify where feedback appears: app, email, dashboard, meeting, artifact, community, physical environment.
   - Completion standard: every target behavior has feedback and a win state.

5. **Define incentives and rewards**
   - List possible status, access, power, and stuff rewards, plus non-material feedback.
   - Completion standard: rewards are linked to drives and do not stand alone.

6. **State tradeoffs**
   - Identify what the design may intentionally under-optimize.
   - Completion standard: the user can see what will change if metric priority changes.

## B — 邊界 (Boundary)

### 不要在以下情況使用此 skill

- The user only needs a quick tactic and the metric/behavior is already clear.
- The problem is not behavior-related.
- The user wants an inspirational mission statement without measurement or action.

### 作者在書中警告的失敗模式

- Teams claim they know the business metric until asked to rank it.
- Optimizing lower-level activity can damage the real goal.
- Every interface element that does not support the target behavior becomes distraction.

### 作者的盲點 / 時代局限

- The source language is business-heavy. For non-business settings, translate metrics into learning, health, research, trust, safety, or relationship outcomes.

### 容易混淆的鄰近方法論

- A project charter covers scope and ownership; this dashboard covers motivation requirements.
- A KPI tree may rank outcomes; this dashboard connects outcomes to actors, target behavior, feedback, and rewards.

## 相關 skills

- depends-on: none when starting from scratch.
- composes-with: `motivation-diagnosis`, `journey-stage-mapping`, `feedback-loop-design`.

## 審計信息

- **驗證通過**: V1 ✓ / V2 ✓ / V3 ✓
- **測試通過率**: 100% (see `test-results.md`)
- **蒸餾時間**: 2026-05-29
