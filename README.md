# git-training
STVの帰社日用のリポジトリです。

## Goals
帰社日に参加した社員の名簿を作成すること

## Tasks

| No. | タスク名 | コマンド等 |
|---|---|---|
|1.| オリジナルリポジトリを自分のリポジトリにForkする | |
|2.| Forkしたリポジトリをローカル環境にクローンする |git clone {自分のリポジトリ名}|
|3.| リモートリポジトリに名前を設定する |git remote add upstream {オリジナルのリポジトリ名}|
|4.| オリジナルリポジトリの変更を取り込む |git fetch upstream|
|5.| リモートリポジトリにあるブランチをローカルリポジトリにチェックアウトする |git checkout -b {ブランチ名}|
|6.| オリジナルリポジトリのブランチの差分を取り込む |git merge upstream/{ブランチ名}|
|7.| 作業用のブランチを作成する | git checkout –b {ブランチ名} |
|8.| ファイルを修正する | |
|9.| 修正したファイルをステージングに上げる |git add {ファイル名} or git add .|
|10.| 編集したファイルをcommitする |git commit –m “コメント”|
|11.| 編集したファイルを自分のリポジトリにPushする | git push origin {ブランチ名} |
|12.| オリジナルリポジトリに向けてPull Requestする | |
|13.|リリースブランチにマージする | |





