# CSS
  A memorandum for studying CSS

## .cssファイルの1行目の記述
CSSファイルのエンコード種類がUTF-8であると明示する。  
@charset 'UTF-8';

## 基本色について
メイン、ダーク、アクセントの3色を決める。
Adobe color CCのwebサイトを参考にする。

## メディアタイプについて（2つだけ）
CSSメディアタイプの種類
-- screen（ディスプレイ）
-- print（プリンタ）

使い方は以下のいずれか
-- htmlファイルに<link media="メディアタイプの記載">
-- CSSがいるに @media メディアタイプの記載{ property:hogehoge };