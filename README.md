# Blog-App
Simple Blog mobile application built with Firebase for the backend and Flutter for the frontend and Cloud Firestore for the DB

## 概要
* プロジェクト名：Blogアプリ開発
* プロジェクトの概要：  
  モバイル/Web上でブログ記事を投稿でるアプリを開発

## 使用技術一覧
- バックエンド：Firebase
- フロントエンド：Flutter
- データベース：Cloud Firestore

## インストール手順
1. このリポジトリをクローンします。
2. ルートディレクトリで以下コマンドを実行
` docker compose up -d --build `


## 使用方法

1. アプリケーションを起動すると、Blogアプリが表示されます。


## 開発に参加する方法

このプロジェクトに貢献したい場合は、以下の手順に従ってください。

1. このリポジトリをフォークします。
2. フォークしたリポジトリをローカルマシンにクローンします。
3. 新しい機能やバグ修正のブランチを作成します。
4. 変更をコミットし、プッシュします。
5. プルリクエストを作成します。

## ブランチ戦略

1. メインブランチ (main/master):
- 本番環境にデプロイされる安定版のコードを反映するブランチ。
- 主にリリースされたバージョンのコードが保持される。
2. 開発ブランチ (develop):
- 開発中の最新の機能や修正を統合するブランチ。
- 新しい機能の開発やバグ修正などの作業が行われる。
3. フィーチャーブランチ (feature branches):
- 個々の機能や修正を開発するためのブランチ。
- 開発者は各自のフィーチャーブランチで作業し、開発が完了したら develop ブランチにマージする。
4. リリースブランチ (release branches):
- 次のリリースの準備をするためのブランチ。
- develop ブランチから作成され、最終テストやバグ修正が行われる。
- リリース準備が整ったら main ブランチにマージされる。
5. ホットフィックスブランチ (hotfix branches):
- 本番環境で緊急修正が必要な場合に使用されるブランチ。
- main ブランチから作成され、修正が行われる。
- 修正が完了したら main ブランチと develop ブランチにマージされる。

## ライセンス

このプロジェクトは MIT ライセンスの下で公開されています。詳細については、[LICENSE](LICENSE) ファイルを参照してください。

