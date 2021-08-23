# Ergotonic49 Spirit of the Willow
 
[English pages](https://translate.google.com/translate?hl=&sl=ja&tl=en&u=https%3A%2F%2Fhanachi-ap.github.io%2Fergotonic49_docs%2F&sandbox=1)

## 自作キーボードキット Ergotonic49 

![](docs/img/img1.jpg)

- 40%メカニカルキーボード。合計49キーにエクストラとして更に+1キー増量中
- 一体型だけど分離型。分離型だけど非分割。 ストレスフリー運用
- ちょうど扱いやすいサイズ感、 細身のスタイリッシュなボディ
- すっと指を伸ばすとそこに自然にキーがある不思議な感覚。Willow配列を採用
- 3つのモード指示兼装飾用のフルカラーLED
- オプションでアンダーグローLEDに対応
- Cherry MK互換キースイッチ対応
- キースイッチを組み立て後にも取り替え可能なホットスワップを採用
- 最大3つのロータリーエンコーダに対応
- 3層サンドイッチ構造でオーソドックスな組み立て方式
- ProMicroとQMK firmware


## キットの入手先

 - [BOOTH hanachi-ya](https://hanachiya.booth.pm/items/3040189)

## ビルドガイド

 -  [Erogotonic 49 ビルドガイド](https://hanachi-ap.github.io/ergotonic49_docs/docs/)

## ファームウェア

 - ソースコード
   
     [hanachi-ap / qmk_firmware](https://github.com/hanachi-ap/qmk_firmware/tree/ergotonic49/keyboards/ergotonic49)

   公式にはマージしていないので上記リポジトリをcloneあるいはforkなどして下さい。

- hexファイル

   [ergotonic49_default.hex](lib/ergotonic49_default.hex)    (ロータリーエンコーダVIA対応バイナリです)


   [ergotonic49_default_v1.hex](lib/ergotonic49_default_v1.hex)    (前バージョンのバイナリ)


- 標準キーマップ
  
   チートシート [keymap_cheatsheet_ergotonic_49.pdf](docs/img/keymap_cheatsheet_ergotonic_49.pdf)


- REMAP
  
  REMAP公式にマージ済み。

  ブラウザで [REMAPサイト](https://remap-keys.app/) にアクセスするだけで簡単にキーマップやLED表示が設定できます。

- VIA用jsonファイル
  
    [ergotonic49_via.json](lib/ergotonic49_via.json)

    VIAを利用する場合は上記ファイルを読み込ませて下さい。

## 物理レイアウト

本体サイズ  359mm x 113mm x 10mm
   
- 実物大レイアウト図 [ergotonic49.pdf](docs/img/ergotonic49.pdf)

## 加工オプション アクリルディフーザー


   
- 加工オプション [アクリルディフューザー](docs/10_acrylic_diffuser.md)
