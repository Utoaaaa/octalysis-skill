---
name: case-pattern-transfer
description: |
  Use when the user wants to learn from an Octalysis case, adapt a known example to a new domain, or avoid copying a surface gimmick. It extracts transferable motivation mechanisms, non-transferable context, and misuse warnings. Do not use to summarize case stories.
source_book: 《遊戲化實戰全書》 周郁凱 Yu-kai Chou
source_chapter: ch.16; Section II; Section III 3.6-3.7
tags: [cases, patterns, analogy, transfer]
related_skills:
  - slug: motivation-diagnosis
    relation: depends-on
  - slug: core-drive-intervention
    relation: composes-with
  - slug: motivation-ethics-review
    relation: composes-with
---

# Case Pattern Transfer

## R — 原文 (Reading)

> "八角框架讓你提出正確的問題。"
>
> — 《遊戲化實戰全書》ch.17

## I — 方法論骨架 (Interpretation)

Case transfer is not copying the visible mechanic. It is extracting why a mechanism worked for a specific actor, behavior, stage, and drive mix.

Every case has transferable and non-transferable parts. Brand trust, audience density, timing, budget, data plumbing, and real-world fulfillment can be decisive.

The method forces an analogy to pass through target behavior, missing drives, intervention drives, feedback medium, and context fit.

If only the surface skin transfers, reject the case.

## A1 — 書中的應用 (Past Application)

### 案例 1: Chipotle celebrity card vs Scarecrow

- **問題**: Free rewards produced weak participation; story/game tied to brand claim produced stronger engagement.
- **方法論的使用**: Compare reward distribution with mission-aligned interaction.
- **結論**: Copying a giveaway would miss the mechanism; interaction must perform the claim.

### 案例 2: Autodesk

- **問題**: A game could easily distract from the product.
- **方法論的使用**: The game required actual product use to solve missions.
- **結論**: Transfer the "desired behavior equals play behavior" pattern, not the adventure theme.

### 案例 3: Quibids

- **問題**: Short-term engagement came from many losers trying to avoid sunk cost.
- **方法論的使用**: Extract as anti-pattern, not success case.
- **結論**: A case can teach what not to transfer.

## A2 — 觸發場景 (Future Trigger)

### 用户會在什麼情境下需要這個 skill?

1. The user asks "can we do something like Patagonia/Duolingo/Waze/etc.?"
2. A team wants inspiration from a case but needs adaptation.
3. A proposed mechanic seems copied from another domain.
4. The user wants a case-pattern library for a new behavior.
5. A case appears successful but may hide non-transferable context.

### 語言信號

- "能不能借鑑這個案例?"
- "把 Patagonia/Apple/Duolingo/Waze 的方法用到我們這裡。"
- "不要照抄，幫我抽象成模式。"
- "這個案例為什麼有效?"
- "哪些部分不能轉移?"

### 與相鄰 skill 的區分

- Use `motivation-diagnosis` to analyze the new context first.
- Use `core-drive-intervention` to design the adapted mechanism.
- Use `motivation-ethics-review` for dark-pattern or pressure-heavy cases.

## E — 可執行步驟 (Execution)

1. **Extract the source case**
   - Capture context, actor, target behavior, missing drives, intervention drives, mechanics, result, and constraints.
   - Completion standard: the case is represented as a mechanism, not story.

2. **Extract transfer pattern**
   - State the abstract pattern in one sentence.
   - Completion standard: the pattern does not name the original brand or surface mechanic.

3. **Map the new context**
   - Compare actor, stage, target behavior, trust, data, resources, and feedback medium.
   - Completion standard: at least three fit factors and three mismatch factors are named.

4. **Adapt or reject**
   - Adapt the pattern if the mechanism fits; reject if only the skin fits.
   - Completion standard: output "transfer", "modify", or "reject" with reasons.

5. **Add misuse warning**
   - State what would go wrong if copied blindly.
   - Completion standard: warning covers ethics and operational context.

## B — 邊界 (Boundary)

### 不要在以下情況使用此 skill

- The user only wants a historical summary.
- The new context has no defined target behavior.
- The case depends on data, brand trust, or resources the new context lacks and cannot approximate.

### 作者在書中警告的失敗模式

- Surface mechanics without core-drive logic create empty shells.
- A game unrelated to expected behavior becomes distraction.
- Case success can come from black-hat pressure that is not sustainable.

### 作者的盲點 / 時代局限

- Many source metrics are historical and presented from the designer side. Treat them as pattern evidence, not as current proof.

### 容易混淆的鄰近方法論

- Benchmarking copies examples.
- Case-pattern transfer extracts mechanisms and rejects bad analogies.

## 相關 skills

- depends-on: `motivation-diagnosis`.
- composes-with: `core-drive-intervention`, `mission-narrative-design`, `motivation-ethics-review`.

## 審計信息

- **驗證通過**: V1 ✓ / V2 ✓ / V3 ✓
- **測試通過率**: 100% (see `test-results.md`)
- **蒸餾時間**: 2026-05-29
