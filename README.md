# VLSI.JP

趣味と愛

## ☆☆☆☆☆記事の追加方法(他人用)☆☆☆☆☆

1. `ファイル名.md`を書く
2. `ファイル名.md`の先頭に以下を追加
```
---
layout: default
title: 記事のタイトル
---
```
3. Cra2yPierr0t.github.ioをforkして`ファイル名.md`をリポジトリに置く
4. `_data/article_list.yml`に以下を追加
```yml
- title: 記事のタイトル
  author: 筆者名
  date: 書いた日
  link: ファイル名.html
```
5. プルリクを出す
6. HAPPY

不明な点があったり↑の手順がダルかったりIndex of VLSI.JPにリンクだけ置きたい場合は@Cra2yPierr0tマデ、私は遍在します。

## ☆☆☆☆☆記事の追加方法(自分用)☆☆☆☆☆

1. `ファイル名.md`を書く
2. `ファイル名.md`の先頭に以下を追加
```
---
layout: default
title: 記事のタイトル
---
```
3. `ファイル名.md`をリポジトリに置く
4. `_data/article_list.yml`に以下を追加
```yml
- title: 記事のタイトル
  author: 筆者名
  date: 書いた日
  link: ファイル名.html
```
5. Push 
6. HAPPY

