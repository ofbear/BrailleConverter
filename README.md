# BrailleConverter
## 概要
音声認識を利用した日本語の点字変換サービス

## 利用方法
- 右上のマイクのマークをクリックし、話しかける
- 上段のテキストエリアにキーボードで文字を打ち込む

いずれかを行うと下段のテキストエリアに点字が出力される

## 詳細
### 音声認識
MDNに策定されているWeb Speech APIを利用
https://developer.mozilla.org/ja/docs/Web/API/Web_Speech_API

現状ではおそらくChromeでしか動かない。（もしかするとFireFoxでも動くかも？）

### 点字変換
下記を利用
https://github.com/uhyo/tenji
https://uhyo.github.io/tenji-web/

# License
MIT