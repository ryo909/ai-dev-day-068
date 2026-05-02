# Day068 Story — Family Photo Caption Rail

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day068専用にテーマをseed固定して再生成時の見た目を安定化
- utility用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: photo_caption_memory_log
- Mechanic: flow_pick
- Input/Output: photo_cards -> choice_cards
- Audience Promise: 写真整理を重くせず、思い出の芯だけ残せる。
- Publish Hook: 写真名と一言を入れると、見返せる短い記録列がすぐできる。
- Complexity Tier: small
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day068｜家族写真ひと言レール
家族写真ひと言レールを作るためのツールです。
