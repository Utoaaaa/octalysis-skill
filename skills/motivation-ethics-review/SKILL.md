---
name: motivation-ethics-review
description: |
  Use whenever a motivation design uses scarcity, FOMO, streaks, loss, penalties, random rewards, mystery boxes, social pressure, public comparison, sunk cost, lock-in, or external incentives. It reviews short-term benefit, long-term fatigue, agency, intrinsic-motivation damage, and safer alternatives. Do not use as a generic moral essay.
source_book: 《遊戲化實戰全書》 周郁凱 Yu-kai Chou
source_chapter: ch.13-ch.14; Section I 1.7; Section II; Section III
tags: [ethics, black-hat, risk, guardrails]
related_skills:
  - slug: motivation-diagnosis
    relation: composes-with
  - slug: core-drive-intervention
    relation: composes-with
  - slug: feedback-loop-design
    relation: composes-with
---

# Motivation Ethics Review

## R — 原文 (Reading)

> "龐大的權力帶來龐大的責任。"
>
> — 《遊戲化實戰全書》ch.13

## I — 方法論骨架 (Interpretation)

Motivation design changes behavior, so every high-pressure mechanism needs an ethics review.

This skill focuses on specific risky mechanisms: scarcity, uncertainty, loss avoidance, social pressure, streaks, sunk cost, external rewards, and lock-in.

The question is not whether a mechanism works. The question is whether it helps actors do something they would endorse on reflection, with clear agency, proportionate pressure, and recovery paths.

The output must include short-term benefit, long-term fatigue risk, loss-of-agency risk, intrinsic-motivation risk, and safer white-hat alternatives.

## A1 — 書中的應用 (Past Application)

### 案例 1: Quibids

- **問題**: Penny auctions used sunk cost and loss avoidance to keep people bidding.
- **方法論的使用**: Identify CD6/CD7/CD8 dominance and missing broad win states.
- **結論**: Engagement can be extractive when many losers fund one winner.
- **結果**: Source treats it as a failure/anti-pattern.

### 案例 2: Arizona park signs

- **問題**: A warning said many visitors stole petrified wood.
- **方法論的使用**: Social norm framing made bad behavior seem normal.
- **結論**: Ethical messaging must avoid normalizing harm.

### 案例 3: Childcare late pickup fine

- **問題**: A fine reframed responsibility as a purchasable service.
- **方法論的使用**: White-hat social responsibility shifted into low-cost loss calculation.
- **結論**: Incentives can change the moral meaning of behavior.

## A2 — 觸發場景 (Future Trigger)

### 用户會在什麼情境下需要這個 skill?

1. A design includes scarcity, countdowns, streaks, penalties, random rewards, or FOMO.
2. A user asks whether a motivation tactic is manipulative.
3. A system shows short-term metric gains but user fatigue or complaints.
4. A reward may crowd out intrinsic motivation.
5. A loop may cause unsafe real-world, financial, social, or mental-health effects.

### 語言信號

- "這樣會不會太操控?"
- "要不要加倒數/連續打卡/隨機獎勵?"
- "短期有效，但長期會不會傷害使用者?"
- "這個 retention loop 有倫理風險嗎?"
- "幫我做 black-hat review。"

### 與相鄰 skill 的區分

- Use this after `core-drive-intervention` if proposed interventions include risky mechanisms.
- Use this during `feedback-loop-design` for re-entry loops.
- Use `motivation-diagnosis` first if there is no concrete design to review.

## E — 可執行步驟 (Execution)

1. **Inventory pressure mechanisms**
   - Identify CD6 scarcity, CD7 uncertainty, CD8 loss, CD5 pressure, CD4 lock-in, and extrinsic rewards.
   - Completion standard: every risky mechanism is named.

2. **State intended benefit**
   - Explain what short-term behavior the mechanism improves.
   - Completion standard: benefit is tied to a target behavior and success metric.

3. **Assess harm**
   - Evaluate fatigue, loss of agency, intrinsic crowd-out, regret, safety, finance, social exposure, and vulnerable-user risk.
   - Completion standard: each risk is classified as low/medium/high.

4. **Check reflective endorsement**
   - Ask whether actors would still endorse the behavior after pressure is removed.
   - Completion standard: if no, mark design as manipulative or reject.

5. **Add guardrails**
   - Provide opt-out, pause, grace, recovery, transparency, limits, portability, or alternative white-hat route.
   - Completion standard: every medium/high risk has a mitigation or rejection.

6. **Output decision**
   - Choose approve, modify, or reject.
   - Completion standard: decision includes rationale and safer alternative.

## B — 邊界 (Boundary)

### 不要在以下情況使用此 skill

- The user asks for legal compliance advice; provide product ethics reasoning, not legal opinion.
- The issue involves clinical addiction, self-harm, or medical risk; advise involving qualified professionals.
- The design is too vague to identify mechanisms.

### 作者在書中警告的失敗模式

- Black-hat mechanics can create urgency, obsession, or addiction while making people feel worse.
- External rewards can crowd out intrinsic motivation.
- Social influence can become shame, pressure, or backfire.
- Sunk-cost designs can trap people.

### 作者的盲點 / 時代局限

- Sources often evaluate risk from design and business outcomes; modern review should also include privacy, consent, vulnerable populations, accessibility, and AI automation effects.

### 容易混淆的鄰近方法論

- Compliance review asks "is this allowed?"
- Motivation ethics review asks "does this preserve agency, trust, and user-endorsed value?"

## 相關 skills

- composes-with: all other skills when risky mechanisms appear.
- contrasts-with: none; this is a guardrail layer, not an alternative design method.

## 審計信息

- **驗證通過**: V1 ✓ / V2 ✓ / V3 ✓
- **測試通過率**: 100% (see `test-results.md`)
- **蒸餾時間**: 2026-05-29
