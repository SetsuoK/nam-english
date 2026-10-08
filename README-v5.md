# NAM English v5

## 目的
iPhoneでの英語音声を、Web/PWAで利用できる範囲でできるだけ自然にする版です。

## v5 の変更
- 全フレーズを iPhone の英語音声で再生
- Premium / Enhanced / Siri 系の音声を自動的に上位へ
- 音声をアプリ内で選択可能
- 再生速度・ピッチを調整可能
- 30秒/60秒スクリプトは文単位に分けて読み上げ、抑揚の崩れを減らす
- 選択した音声・速度・ピッチを保存
- Service Worker を v5 に更新して旧キャッシュを破棄

## GitHub で置き換えるもの
- index.html
- service-worker.js
- manifest.json（既存のものがあれば、既存版を残しても構いません）

## iPhone 側
1. SafariでGitHub Pagesを一度開く
2. ホーム画面の旧版を削除
3. Safariの共有 → ホーム画面に追加
4. アプリ上部の音声一覧で、Premium / Enhanced / Siri と表示される英語音声があれば選択
5. 「音声テスト」で確認
6. 速度は0.88〜0.95程度がおすすめ

注意: Safari/PWAの音声品質は、iPhoneにインストールされている英語音声に依存します。
