# コーディングルール

基本的に下記の記事のコーディング規約に従う.

https://qiita.com/simonritchie/items/bb06a7521ae6560738a7

# プッシュについて

自分が担当する機能の実装が終わったら、自分が作業しているブランチからmasterブランチにプッシュする。

その際は【プルリクエスト】をして他の人にコードをレビューしてもらう。

プルリクエストするときには動作確認ができている場合に限る。

# テストについて
基本的に１メソッド作ったら単体テストを行う。

テストのために作成したコードはtestディレクトリに入れる。

単体テストのために使用するライブラリについては以下を参照。

https://qiita.com/aomidro/items/3e3449fde924893f18ca

テストが終了したらテストケース数とテストカバレッジ率を記録する。

※2020/4/12（日）現在何で管理するかは未定

