# 課題８ -オススメの本の登録アプリ-

## ①課題内容（どんな作品か）
- オススメの本を登録する

## ②工夫した点・こだわった点
- 前回の課題７は、text内にデータを保管したので、今回はDBに登録しました。
- 大好きな、csv出力ができるようにしました。（fputcsv関数を使用しました）
- 最初の登録フォームで、登録ずみの一覧が見られるようにしました。ただし、個人情報を考えてE-mail は表示しないようにしました
- 最初の登録フォームで、adminと打つとボタンが表示され、管理画面に行くようにしました。
- 管理画面で、csv出力が出来る、チャートが見られるようにしました

## ③難しかった点・次回トライしたいこと(又は機能)
- csvの出力はしたのですが、csvでデータをインポートしようとしましたが、エラーになってうまくいかなかった。次回はデータベースの権限などの理解を深めたい
- いいねボタンや、登録された本に対して他の人もコメントできるようにしようかと思ったが、DBの設計がうまくいかなかったので、次回はチャレンジしてみたい
- 今回までは、フレームワークは使わなかったので、フレームワークも使えるようにしたい
- API連携をしてデータを登録して、というところもやってみたいと思いました。reactで作ったFirebaseのアプリや、Localstrageに保存しているアプリなども、DB構築のチャレンジをしてみたい

## ④質問・疑問・感想、シェアしたいこと等なんでも
- [質問] cssがうまく当たらないので、試行錯誤しています。今回も別ファイルのcssを使ったりPHPに直接書いたりして調整しました。何かコツがあるのでしょうか？
- [感想] 今回は前回のものをアップデートしようと思ったので、それほど辛くはありませんでした。そのため、ちょっとPythonを触ったり、Ruby　on railの環境構築をしたりしていましたが、こちらは難しく、どのように全体を仕上げていけばいいか悩むきっかけになりました。
- [参考記事] 
	- 1.(https://www.sejuku.net/blog/25648)　　　　（csv出力）
