---
sidebar_position: 1
---

# コントリビューティングルール
## 書き方
tasurenが考案した[このコードスタイル](https://gist.github.com/tasuren/bf1fcce48f1e23a5c7e6abd503bdb3c1)に基本は従ってください。  
現状のRTのコードのほぼ全てがこのスタイルに沿っています。

## 型チェッカー
[pyright](https://pypi.org/project/pyright/)を使用しています。  
pyrightの型検出(basicモード)を使って型チェックをして型エラーがないようにしてください。

## コミットメッセージ
`fix: 明確な変更内容`のように最初にどのような変更かを表す動詞を、右に内容を書いてください。  
以下のような動詞がよく使われます。
```
fix     修正
improve 改善
update  更新
```
内容の最後には句点をつけるようにすると好ましいです。  
例：`improve: いらないimportを消した。`

## SQLの書き方
大文字で書いてください。  
最後に必ず`;`を置いてください。  
テーブル名とコラム名はアッパーパスカルケースにしてください。