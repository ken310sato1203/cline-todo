# cline-todo

CLI todo アプリケーションのプロジェクトです。

## 機能

- ✅ タスクの追加・削除・編集
- ✅ タスクのカテゴリ分け（仕事、家事、学習など）
- ✅ 優先度管理（高・中・低）
- ✅ スターやコメント付きタスク
- ✅ 統計データ表示

## プロジェクト構造

```
cline-todo/
├── README.md          # プロジェクトの説明
├── .gitignore         # Git で追跡しないファイルの指定
├── src/               # ソースコード
│   ├── cli.ts         # CLI メインエントリーポイント
│   └── todo.ts        # Todo 機能の実装
├── tests/             # テストケース
└── package.json       # Node.js パッケージ設定
```

## インストール

### クローン

```bash
git clone https://github.com/ken310sato1203/cline-todo.git
```

### 環境準備

- Git がインストールされていること
- （Node.js の場合）Node.js 18.x またはより新しいバージョン

```bash
npm install
```

## 使い方

### タスクの追加

```bash
yarn add todo \\
  --title "タスクタイトル" \\
  --description "タスクの説明" \\
  --priority "high|medium|low" \\
  --category "仕事|家事|学習|その他"
```

### タスクリストの表示

```bash
yarn list
```

### 完了したタスクのマーク

```bash
yarn complete <todo_id>
```

## リソース管理

このリポジトリは、以下のようなリソースを利用しています：

- Git: https://git-scm.com/
- Node.js: https://nodejs.org/

## 貢献方法

1. Fork を作成
2. ブランチを作成 (`git checkout -b feature/AmazingFeature`)
3. 変更を加える (`git commit -m 'Add some AmazingFeature'`)
4. プルリクエストを作成 (`git push origin feature/AmazingFeature`)

## ライセンス

このプロジェクトは MIT ライセンスの下でライセンスされています。

## お問い合わせ

何か質問やご意見があれば、Issue を作成してください。
