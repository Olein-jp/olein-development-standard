# Olein Development Standard

Olein Development Standard（ODS）は、人間と AI が共通の判断基準で Web プロダクトを設計・開発・保守するための汎用的な開発標準です。

ODS は、特定のフレームワーク、言語、CMS、AI ツールに依存しません。まず Web プロダクト全般に共通する思想と開発ルールを定義し、必要に応じて WordPress、React、Astro、Laravel などの固有ルールを追加していきます。

## Purpose

ODS の目的は、開発に関わる人間と AI が、同じ基準で判断できる状態を作ることです。

特に、次のような場面で判断のブレを減らすことを目指します。

- MVP の範囲を決めるとき
- 実装方針に迷ったとき
- UX と開発都合が衝突したとき
- 保守性と開発速度のバランスを取るとき
- AI が自律的に作業する範囲を判断するとき
- ドキュメント、仕様、実装の整合性を保つとき

## Core Principles

ODS v0.1 では、以下の原則を最小構成として定義します。

1. User First
2. MVP First
3. UX First
4. Maintainability
5. Simplicity
6. YAGNI
7. Documentation as Source of Truth
8. AI Collaboration
9. Efficiency First

## Scope of v0.1

ODS v0.1 では、まず形にすることを優先します。

含めるものは次の5ファイルのみです。

```text
README.md
AGENTS.md
MANIFEST.md
docs/00_PHILOSOPHY.md
docs/10_DEVELOPMENT.md
```

WordPress 固有ルール、セキュリティ詳細、テスト詳細、リリース運用などは v0.2 以降で追加します。

## How to Use

新しいプロダクトでは、まず次の順序で参照します。

1. `MANIFEST.md`
2. `docs/00_PHILOSOPHY.md`
3. `docs/10_DEVELOPMENT.md`
4. 各プロダクト固有の仕様書

ODS はチャットログではなく、開発判断の正本として扱います。

## Status

Current version: `v0.1-draft`

ODS は、実際のプロダクト開発で使いながら必要に応じて改善していく、生きた開発標準です。
