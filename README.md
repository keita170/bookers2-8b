# bookers7-9の応用課題a,b,dが入ってます

* ここはbookers2の7b-9bの処理が入ってます

* 7bは投稿数の表示をさせる。今日と昨日。そして前日比も出す。同じく今週と先週の投稿数を表示させて、前週比を表示させる。

* 8bは過去1週間の投稿数を1日1日表示させる。chart.jsを使って過去7日間の投稿をグラフ化する。

* 9bはユーザーの詳細ページに指定した日付の投稿数を表示させる(非同期で)機能を追加する。

* bookers2-6までで、フォローフォロワー機能、検索機能、非同期でのいいね、コメント機能を実装してます

* ...

## いいね順並び替え機能、DM機能、閲覧数表示機能

投稿数の表示、前日、前週との比率を表示させる機能
1週間の投稿数を表示させchart.jsを用いて表示、選択した日付の投稿数を表示させる検索機能実装(非同期)

* scopeを用いて昨日、今週、前週期間を記述した
* チャート実装では、turbolinksを無効化して実装しました
* f.date_fieldを用いて、日付選択ができるフィールドを作成

 ## 開発環境
 - OS：Linux(CentOS)
 - 言語：HTML,CSS,JavaScript,Ruby,SQL
 - フレームワーク：Ruby on Rails
 - JSライブラリ：jQuery
 - IDE：Cloud9
