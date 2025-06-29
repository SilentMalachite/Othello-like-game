# オセロゲーム (Othello Game)

![Othello Game](https://img.shields.io/badge/Game-Othello-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

シンプルで直感的な**オセロ（リバーシ）ゲーム**のWebアプリケーションです。ブラウザ上で動作する軽量なゲームで、外部依存なしで楽しめます。

## 🎮 特徴

- **完全スタンドアロン**: 単一のHTMLファイルで動作
- **レスポンシブデザイン**: PC・タブレット・スマートフォンに対応
- **アクセシビリティ対応**: キーボード操作・スクリーンリーダー対応
- **視覚的フィードバック**: 有効な手をハイライト表示
- **直感的UI**: 日本語インターフェース
- **リアルタイムスコア**: 黒白のディスク数をリアルタイム表示

## 🚀 使い方

### 簡単スタート
1. `othello.html` をダウンロード
2. ブラウザで開く
3. すぐにプレイ開始！

### オンラインでプレイ
ファイルをWebサーバーにアップロードするか、GitHub Pagesなどの静的ホスティングサービスで公開できます。

## 🎯 ゲームルール

### 基本ルール
1. **8×8のボードで対戦**: 黒と白が交互に手番
2. **相手のディスクを挟む**: 縦・横・斜めに相手のディスクを挟んでひっくり返す
3. **黒が先手**: ゲーム開始時は黒が最初に打つ
4. **パス**: 置ける場所がない場合は自動的にパス
5. **ゲーム終了**: 両者が打てなくなるか、ボードが埋まったら終了

### 勝敗判定
最終的にディスクの数が多い方の勝利です。

## 🎨 インターフェース

- **黄色い点**: 現在打てる有効な手を表示
- **リアルタイムスコア**: 右パネルに黒白の現在のスコアを表示
- **ターン表示**: 現在どちらの手番かを表示
- **パス通知**: パスが発生した場合は3秒間メッセージを表示
- **ゲーム終了**: 勝敗結果をステータスエリアに表示

## 🖥️ 技術仕様

### 使用技術
- **HTML5**: セマンティックなマークアップ
- **CSS3**: モダンなスタイリング（Grid Layout、Flexbox）
- **Vanilla JavaScript**: フレームワーク不使用の軽量実装

### ブラウザ対応
- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

### パフォーマンス最適化
- 差分更新によるDOM操作の最小化
- CSS Gridによる効率的なレイアウト
- イベント委譲によるメモリ効率の向上

## 🌟 改善された機能

このバージョンでは以下の問題を修正・改善しています：

- ✅ **パス処理のロジック修正**: 正確なターン管理
- ✅ **ホバーエフェクト改善**: 空のセルのみにエフェクト
- ✅ **有効手の可視化**: 打てる場所を黄色い点で表示
- ✅ **UI通知改善**: alertの代わりに画面内メッセージ
- ✅ **レスポンシブ対応**: モバイルデバイスでの最適表示
- ✅ **アクセシビリティ向上**: ARIA属性とキーボード操作
- ✅ **パフォーマンス最適化**: 差分更新による高速化

## 🛠️ 開発

### ローカル開発
```bash
# リポジトリをクローン
git clone https://github.com/SilentMalachite/othello-game.git

# ファイルをブラウザで開く
open othello.html
```

### カスタマイズ
- **ボードサイズ**: `BOARD_SIZE` 定数を変更（8以外は非推奨）
- **色テーマ**: CSS変数でカラーパレットをカスタマイズ可能
- **アニメーション**: CSS transitionで動作速度を調整

## 📝 ライセンス

MIT License - 詳細は [LICENSE](LICENSE) ファイルを参照してください。

## 🤝 コントリビューション

プルリクエストや機能提案を歓迎します！

1. このリポジトリをフォーク
2. 機能ブランチを作成 (`git checkout -b feature/amazing-feature`)
3. 変更をコミット (`git commit -m 'Add some amazing feature'`)
4. ブランチにプッシュ (`git push origin feature/amazing-feature`)
5. プルリクエストを作成

## 📞 サポート

- バグ報告: [Issues](https://github.com/yourusername/othello-game/issues)
- 機能リクエスト: [Issues](https://github.com/yourusername/othello-game/issues)

---

⭐ このプロジェクトが気に入ったら、スターをお願いします！
