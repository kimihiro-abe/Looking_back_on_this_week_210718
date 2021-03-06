# Looking back on this week(210718)
今週もGuthubのテスト込みで、今週あったことを記載しておきます。  
（使わないと使い方を忘れてしまいそうで...）

## - 訓練校関連 - （訓練校であったことで、メモ＆考えたことなど記載）
7/2（金）から始まったチーム実習。今週は、実質的に第二週目。  
<br>

### - 今週こなした自分の作業
- ロバストネス図の修正（ゲスト、ユーザー部分のみ）  
修正漏れ箇所、共通処理や流用して応用出来そうな部分について記述を追加
- 他メンバーの制作したクラス図の修正・検討  
DAOとそれにつながるbeanまわりの詳細詰め。
- 工程表の随時更新・共有  
次のレビューに提出する部分を決め、それに対してスケジュールを切りチームメンバーへ共有
- データベース（以降DB）まわりの設計（必須要件とそれ以外の要件の最小構成を決定）  
ダミーデータを準備するために、最小構成でDBを構成することにしました。
- プロジェクトファイルの初回設定と共有  
web.xml,content.xmlへの記載、そしてDBへ繋ぎこんだ最低限設定を作りSVNで共有
- プログラミング(サーブレット、JSP)  
ログイン・ログアウト機能の実装（入力の妥当性確認機能はレビュー後対応）  
DB検索機能の実装～検索結果一覧表示（入力の妥当性確認機能はレビュー後対応）  
DB内コンテンツの詳細情報表示部分の実装（検索結果から詳細表示にいたるつなぎはレビュー後対応）
- 仲間のプログラミング・ヘルプ(サーブレット、JSP)  
レビュー一覧表示機能実装のヘルプ（入力の妥当性確認機能はレビュー後対応）  
ユーザー登録機能実装のヘルプ（入力の妥当性確認機能はレビュー後対応）  
- その他（上記に関係する話し合いメインなど）  

<hr>

## - チーム作業雑感（実質的第二週目の） -  
### - 作業の進め方の話
諸々初期設計（UML図まわり）を一段落させ、  
プログラミングを開始したことが今週一番のトピックでした。  
<br>
当初、「どこからどういうふうに進めるのか？」という懸念がメンバー間であり、  
パーツ毎（JSP/サーブレット他）にどうするかを考えていたメンバーもいました。  
<br>
しかし、MVCモデルへの理解度の差がメンバー間でもだいぶあるので、  
この状況でパーツ毎に分割して作業を個々に振り分けてしまうと、   
余計に混乱を来たしてしまうことが見えていました。  
<br>
また、１つの機能を１人で実装しきった方が経験値を多く積めるだろうし、  
今後の作業を進めるうえでも利点があると私は考え、  
「１人が１つの機能を実装しきる」ことを提案し、  
それが受け入れられ作業を進めることになりました。  
<br>

### - 前職での経験を生かしつつ...
まだ、チーム作業を開始して二週間弱ではありますが、  
前職（サウンドデザイナー職）での経験をプログラミングの作業においても  
生かせる場面は多くあるだろうと感じました。  
<br>
優先度をつけて仕事をする部分や、  
問題を小分けして出来る箇所から着手するといったことなど、  
意外に思われるかもしれませんが音楽制作でも同様です。  
<br>
また、音楽制作というと個人作業のように思われることが多いのですが、  
演奏者さんや編曲家さんとお互いにアイデアを出し合い、  
より良い音楽を共同で作っていく過程などは、  
プログラミングのチーム作業とほぼ変わりがありません。  
<br>
これまでとは異なる職を目指すにあたり、  
全てがゼロからの出発ではなく、  
これまで培った技術・経験・知識で使えるものが多少なりあると思います。
<br>  
応用可能なものを使いつつ、新たなものを積極的に取り入れ、  
柔軟性を持ちつつ貪欲に仕事に取り組んでいきたいと思いました。
