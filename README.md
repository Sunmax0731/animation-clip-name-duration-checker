# Animation Clip命名・尺検品

animation-clip-name-duration-checker は Unity/Blender間でAnimation Clipを整理する制作者 向けの closed alpha プロダクトです。Clip名、尺、ループ設定、用途、基準との差分を確認し、インポート前の戻しを減らす。

## Source

- PICKUP Rank: 54
- Domain / Idea No: AssetPipeline / 4
- Repository: animation-clip-name-duration-checker
- 主な公開先: GitHub Release / BOOTH
- created_idea: `D:/AI/AssetPipeline/created_idea_004_animation-clip-name-duration-checker`
- 同梱ZIP: `D:/AI/AssetPipeline/created_idea_004_animation-clip-name-duration-checker/idea_004_animation-clip-name-duration-checker.zip`
- 開始時 README: 存在しない


## Alpha Scope

- 代表シナリオ4件の自動検証
- 必須項目不足、警告、混在バッチの分類
- src/cli/ のホスト連携シェル
- QCDS、security/privacy、traceability、release checklist、manual test docs
- docs ZIP: `dist/animation-clip-name-duration-checker-docs.zip`

## Commands

```powershell
npm test
node src/cli/index.js samples/representative-suite.json
npm run build:docs
```

手動テストは Codex 側では未実施です。手順は `docs/manual-test.md` と `docs/strict-manual-test-addendum.md` にあります。

