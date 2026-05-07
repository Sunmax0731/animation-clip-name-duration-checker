# 要件定義

## 目的

Animation Clip命名・尺検品 は、Unity/Blender間でAnimation Clipを整理する制作者 が Clip名、尺、ループ設定、用途、基準との差分を確認し、インポート前の戻しを減らす。

## Source

- PICKUP Rank: 54
- Domain / Idea No: AssetPipeline / 4
- Repository: animation-clip-name-duration-checker
- created_idea: `D:/AI/AssetPipeline/created_idea_004_animation-clip-name-duration-checker`
- ZIP: `D:/AI/AssetPipeline/created_idea_004_animation-clip-name-duration-checker/idea_004_animation-clip-name-duration-checker.zip`
- README確認: 開始時点では正式 repo が存在しないため、README.md は存在しない。

## Functional Requirements

- R1: clipName、durationSec、loopMode、usage を必須項目として検査する。
- R2: 必須項目不足は fail として分類する。
- R3: `durationOutOfRange` が true の場合は warning として分類し、手動確認理由を返す。
- R4: 複数アイテムの mixed-batch を pass / warning / fail に集計する。
- R5: 結果を CLI と docs/release evidence で再利用できる形にする。

## Non Functional Requirements

- UTF-8 で Markdown / JSON / JS / HTML / Python を保存する。
- 外部通信を既定で行わず、サンプルとローカル入力だけで検証できる。
- 手動テスト未実施であることを release 前 docs に明記する。

