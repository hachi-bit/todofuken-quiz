# todofuken-quiz

都道府県のシルエット（黒塗り）を見て、都道府県名を漢字で入力して当てるクイズゲームです。

- ビルド不要・インストール不要の静的Webアプリ（`index.html` 1ファイル）
- スマホ・PCブラウザで動作
- GitHub Pages で公開: `hachi-bit.github.io/todofuken-quiz/`

## 遊び方

1. 「通常モード」または「苦手だけモード」を選ぶ
2. 表示されたシルエットの都道府県名を漢字で入力して回答
3. 全問終えると結果画面で正解数を確認できる

進捗（1回でも正解した都道府県）は端末の `localStorage` に保存されます。

## 使用素材・ライセンス

都道府県地図データ: [geolonia/japanese-prefectures](https://github.com/geolonia/japanese-prefectures)
（Wikipedia『日本地図.svg』を改変、GFDL）
