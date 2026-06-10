# w-kikosha--site

w-kikosha 屋号のサイトリポジトリ。GitHub Pages で `docs/` を公開する。

## ディレクトリ構成とオーナー

```
docs/          ← GitHub Pages（公開領域）
  _site/       ← w-kikosha--site 管理（トップページ・共通リソース）
  {app}/       ← 各アプリプロジェクトが管理

src/           ← 非公開領域（GitHub Pages に含まれない）
  _site/       ← w-kikosha--site 管理（素材・設計メモ等）
  {app}/       ← 各アプリプロジェクトが管理
```

## 書き込みルール

| ディレクトリ | 書き込み可能なプロジェクト |
|---|---|
| `docs/_site/` | w-kikosha--site のみ |
| `docs/simple-register/` | simple-register プロジェクトのみ |
| `src/_site/` | w-kikosha--site のみ |
| `src/simple-register/` | simple-register プロジェクトのみ |

新しいアプリを追加するときは `docs/{app}/` と `src/{app}/` を作り、このテーブルに追記する。

## AI セッションからの操作

- `simple-register` プロジェクトのセッション → `docs/simple-register/` と `src/simple-register/` のみ操作
- サイト全体の変更（トップページ等）が必要な場合は w-kikosha--site を別セッションで開く
