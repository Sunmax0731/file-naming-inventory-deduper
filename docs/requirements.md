# 要件定義

## 目的

ファイル命名・棚卸し・重複整理 は、納品物、素材、作業フォルダを安全に整理したいWindows利用者 が ファイル名、用途、重複候補、予定アクションを棚卸しし、削除前に確認できる。

## Source

- PICKUP Rank: 45
- Domain / Idea No: WindowsApp / 3
- Repository: file-naming-inventory-deduper
- created_idea: `D:/AI/WindowsApp/created_idea_003_file-naming-inventory-deduper`
- ZIP: `D:/AI/WindowsApp/created_idea_003_file-naming-inventory-deduper/idea_003_file-naming-inventory-deduper.zip`
- README確認: 開始時点では正式 repo が存在しないため、README.md は存在しない。

## Functional Requirements

- R1: filePath、currentName、proposedName、action を必須項目として検査する。
- R2: 必須項目不足は fail として分類する。
- R3: `destructiveAction` が true の場合は warning として分類し、手動確認理由を返す。
- R4: 複数アイテムの mixed-batch を pass / warning / fail に集計する。
- R5: 結果を CLI と docs/release evidence で再利用できる形にする。

## Non Functional Requirements

- UTF-8 で Markdown / JSON / JS / HTML / Python を保存する。
- 外部通信を既定で行わず、サンプルとローカル入力だけで検証できる。
- 手動テスト未実施であることを release 前 docs に明記する。

