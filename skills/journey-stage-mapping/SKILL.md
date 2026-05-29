---
name: journey-stage-mapping
description: |
  Use when motivation changes across time: first contact, first use, repeated behavior, maturity, fatigue, churn, or expert contribution. It maps Discovery, Onboarding, Scaffolding, and Endgame for any behavior journey. Do not use for a single isolated one-time action unless stage transition matters.
source_book: 《遊戲化實戰全書》 周郁凱 Yu-kai Chou
source_chapter: ch.3, ch.16; Section I 1.9; Section III 3.3
tags: [journey, lifecycle, retention, onboarding]
related_skills:
  - slug: strategy-dashboard
    relation: depends-on
  - slug: motivation-diagnosis
    relation: composes-with
  - slug: feedback-loop-design
    relation: composes-with
---

# Journey Stage Mapping

## R — 原文 (Reading)

> "第一天的理由經常與第一百天的理由大不相同。"
>
> — 《遊戲化實戰全書》ch.3

## I — 方法論骨架 (Interpretation)

Motivation is not static. A person tries, starts, repeats, and matures for different reasons.

Journey-stage mapping splits a behavior into Discovery, Onboarding, Scaffolding, and Endgame, then asks what drives support the target behavior in each stage.

The method prevents two common errors: optimizing only the first conversion, and using early-stage novelty as if it could sustain long-term behavior.

The output is a stage-by-stage motivation map with drop-off hypotheses and stage-appropriate interventions.

## A1 — 書中的應用 (Past Application)

### 案例 1: Waze

- **問題**: The same navigation product creates different motivation at first exposure, first use, regular driving, and long-term expert use.
- **方法論的使用**: Analyze CD1/CD2/CD3/CD4/CD5/CD7/CD8 by stage.
- **結論**: Early mission and novelty must evolve into personalization, contribution, community, and long-term value.
- **結果**: Waze is used as a full lifecycle analysis.

### 案例 2: YukaiChou.com desired actions

- **問題**: Site visitors, subscribers, learners, workshop buyers, and premium members are at different journey stages.
- **方法論的使用**: Desired actions are listed separately for Discovery, Onboarding, Scaffolding, and Endgame.
- **結論**: Each stage needs its own target actions and feedback.
- **結果**: The source uses this as a design blueprint.

## A2 — 觸發場景 (Future Trigger)

### 用户會在什麼情境下需要這個 skill?

1. Signup is strong but activation, retention, or completion is weak.
2. A habit starts but fades after novelty.
3. Advanced users have no meaningful next role.
4. The same motivation tactic is being used across the whole lifecycle.
5. A course, onboarding, agent workflow, or community needs staged design.

### 語言信號

- "剛開始有效，後面就沒用了。"
- "使用者註冊後不知道下一步。"
- "老手沒有事情做。"
- "我要設計 discovery/onboarding/retention/endgame。"
- "這個行為旅程在哪裡掉人?"

### 與相鄰 skill 的區分

- Use `strategy-dashboard` first if target behaviors by stage are undefined.
- Use `feedback-loop-design` for the repeated Scaffolding loop.
- Use `motivation-diagnosis` if the stage failure needs CD1-CD8 explanation.

## E — 可執行步驟 (Execution)

1. **Split the journey**
   - Define Discovery, Onboarding, Scaffolding, Endgame for the specific behavior.
   - Completion standard: each stage has actor mindset and stage goal.

2. **List target behaviors by stage**
   - Identify one to three observable actions per stage.
   - Completion standard: no stage is described only as a feeling.

3. **Map stage drives**
   - Identify current and needed CD1-CD8 drivers per stage.
   - Completion standard: each stage has a primary drive and supporting drives.

4. **Find transition failures**
   - Diagnose where actors fail to move from one stage to the next.
   - Completion standard: each drop-off has a motivation hypothesis.

5. **Design stage interventions**
   - Propose stage-specific trigger, feedback, win state, and next action.
   - Completion standard: interventions do not rely on the same mechanic everywhere.

## B — 邊界 (Boundary)

### 不要在以下情況使用此 skill

- The behavior is truly one-time and has no lifecycle.
- The user only needs a single message or CTA.
- The actor is not expected to return, learn, mature, or advocate.

### 作者在書中警告的失敗模式

- Treating a product as one static experience.
- Neglecting Endgame, so mature users leave after exhausting novelty.
- Assuming a stage drive automatically carries into later stages.

### 作者的盲點 / 時代局限

- Source stages come from product/game language; translate them carefully for personal habits, learning, research, and workplace routines.

### 容易混淆的鄰近方法論

- A customer journey map often describes touchpoints.
- Motivation journey mapping describes changing reasons to act.

## 相關 skills

- depends-on: `strategy-dashboard`.
- composes-with: `motivation-diagnosis`, `feedback-loop-design`, `core-drive-intervention`.

## 審計信息

- **驗證通過**: V1 ✓ / V2 ✓ / V3 ✓
- **測試通過率**: 100% (see `test-results.md`)
- **蒸餾時間**: 2026-05-29
