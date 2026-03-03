# Task (Benchmark) — Approval Workflow Service

本リポジトリは input-only spec repo です。  
この `task.md` は、別リポジトリ/別工程（出力側）で生成・実装すべき内容を定義します。

## Inputs (this repo)

- `spec/`
- `assumptions.md`

## Outputs (generated elsewhere)

- 仕様に基づく Approval Workflow Service の実装
- 機械可読な API 契約（例: OpenAPI）
- （任意）テスト/CI

## Acceptance Criteria (minimum)

- 承認要求（request）と承認タスク（task）を含む基本フローが成立する
- 状態遷移（DRAFT→...）が仕様と整合する
