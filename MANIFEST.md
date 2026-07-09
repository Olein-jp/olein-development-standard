# ODS Manifest

このファイルは、Olein Development Standard（ODS）の入口です。

人間と AI は、作業前にこのファイルを確認し、必要なドキュメントだけを参照してください。

## Documents

| Path | Purpose | Read When |
|---|---|---|
| `README.md` | ODS の概要 | ODS を初めて読むとき |
| `AGENTS.md` | AI 向けの作業ルール | AI が ODS を参照して作業するとき |
| `docs/00_PHILOSOPHY.md` | 開発思想と判断基準 | 常に最初に確認する |
| `docs/10_DEVELOPMENT.md` | 汎用的な開発ルール | 仕様策定・実装・レビュー時 |

## Reading Policy

AI は、常にすべてのドキュメントを読む必要はありません。

MUST:
- 作業目的に必要なドキュメントだけを読む。
- 不足がある場合だけ追加で読む。
- 既に読んだ内容を不要に読み直さない。
- 重要な判断で迷う場合は `docs/00_PHILOSOPHY.md` を優先する。

SHOULD:
- 変更対象に近いドキュメントを優先して読む。
- 回答や作業内容を必要以上に長くしない。
- ただし、品質や安全性に必要な確認は省略しない。

## Version

Current version: `v0.1-draft`

## v0.1 Scope

ODS v0.1 では、まず以下の最小構成を完成させます。

- ODS の概要
- AI 向け作業入口
- 開発思想
- 汎用開発ルール

v0.1 では、特定プラットフォーム固有の詳細ルールは扱いません。
