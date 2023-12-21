## branches

| branch  | use                          | base    |
| ------- | ---------------------------- | ------- |
| main    | 製品ブランチ                 | -       |
| develop | 開発ブランチ                 | -       |
| feature | 機能追加・改善作業用ブランチ | develop |

### namig

#### feature branch

feature/[機能概要] 例：feature/course-detail-page

- ケバブケースを使用すること
- 小文字を使用すること

## commit

コミット単位がお客様への成果物・レビューの一塊であることを意識する。  
以下の場合は squash でコミットをまとめること。

- WIP コミットが含まれる
- 同じファイルや同じ機能に対する複数の小規模なコミットが含まれる

### log message

[type] title 　例：[feat] コース詳細ページの作成

#### type

| 種別 | 用途                             |
| ---- | -------------------------------- |
| feat | 新機能の追加・機能改善           |
| fix  | 機能の修正                       |
| docs | ドキュメンテーションの追加・変更 |

## pull requests

1 作業、1 修正ごとに出すことを意識する。  
1PR がお客様への成果物・レビューの単位であることを意識する。

### title

実装内容を簡潔にまとめる

### description

pull_request_template.md テンプレートの内容を記載してレビューを出す。  
※pull_request_template.md をルート直下に配置することで PR テンプレートとして使用できる。

<details>
<summary>pull_request_template.mdテンプレート</summary>
  
```
## チケット(Issue番号)

## 変更点

## 実装根拠(仕様書や Figma のリンク)

## レビュー観点

```

```
