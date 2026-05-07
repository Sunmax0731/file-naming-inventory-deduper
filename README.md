# ファイル命名・棚卸し・重複整理

file-naming-inventory-deduper は 納品物、素材、作業フォルダを安全に整理したいWindows利用者 向けの closed alpha プロダクトです。ファイル名、用途、重複候補、予定アクションを棚卸しし、削除前に確認できる。

## Source

- PICKUP Rank: 45
- Domain / Idea No: WindowsApp / 3
- Repository: file-naming-inventory-deduper
- 主な公開先: GitHub Release / BOOTH
- created_idea: `D:/AI/WindowsApp/created_idea_003_file-naming-inventory-deduper`
- 同梱ZIP: `D:/AI/WindowsApp/created_idea_003_file-naming-inventory-deduper/idea_003_file-naming-inventory-deduper.zip`
- 開始時 README: 存在しない


## Alpha Scope

- 代表シナリオ4件の自動検証
- 必須項目不足、警告、混在バッチの分類
- ui/ のホスト連携シェル
- QCDS、security/privacy、traceability、release checklist、manual test docs
- docs ZIP: `dist/file-naming-inventory-deduper-docs.zip`

## Commands

```powershell
npm test
node src/cli/index.js samples/representative-suite.json
npm run build:docs
```

手動テストは Codex 側では未実施です。手順は `docs/manual-test.md` と `docs/strict-manual-test-addendum.md` にあります。

