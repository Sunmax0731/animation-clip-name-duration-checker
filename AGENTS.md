# AGENTS

この repo は `animation-clip-name-duration-checker` の closed alpha 実装単位です。

## Scope

- Root: `D:\AI\AssetPipeline\animation-clip-name-duration-checker`
- Domain: AssetPipeline
- Product kind: asset-pipeline
- Source pack: `D:/AI/AssetPipeline/created_idea_004_animation-clip-name-duration-checker/idea_004_animation-clip-name-duration-checker.zip`
- Public repo: `https://github.com/Sunmax0731/animation-clip-name-duration-checker`

## Working Rules

- README、AGENTS、SKILL、docs を同じ変更単位で更新する。
- created_idea は `D:/AI/AssetPipeline/created_idea_004_animation-clip-name-duration-checker` を正とし、同梱 ZIP の `metadata.json` と repo 名が一致することを確認する。
- ZIPサイズや生成時刻のように揺れる値を QCDS の固定評価根拠にしない。
- mojibake 判定は `npm test` 内の `scripts/check-mojibake.js` で行う。
- 手動テストは Codex では実施しない。未実施項目を docs に残して release notes にも転記する。
- 作業ブランチは `codex/closed-alpha-release` の1本だけを使い、完了後にローカル/リモートから削除する。

