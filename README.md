#  ActionSheet(タスク管理アプリ)
デプロイ先：[ActionSheet](https://action-sheet.herokuapp.com/)

- スリープ状態の場合があります。その場合、起動まで10秒程度お待ちください。

## 概要
タスク管理アプリケーションを作成

- Ruby on Railsにて開発。
- HTML/CSS/Bootstrapを使用して、実際のTrelloを意識したデザインを適用。
- リスト・カードの一覧表示、カードの詳細、編集、更新、削除機能の実装
- ログイン機能を実装。
- 一対多、多対多関係の実装

## 環境、フレームワーク 
- Ruby  -v 2.6.3
- Ruby on Rails -v 5.2.3
- Bootstrap v4
- PostgreSQL
- Heroku 

## 使い方

```bash
brew install postgresql
brew services start postgresql
git clone https://github.com/ryu-silver/ActionSheet.git
cd ActionSheet
bundle install
rails db:migrate
rails s
```
