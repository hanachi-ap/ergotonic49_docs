# キーボードをカスタマイズする

Ergotonic-49をカスタマイズする方法は、大きく次の2つの方法があります。
  1. [REMAP](https://remap-keys.app/)を用いて、直感的にキーマップを変更する方法
  2. [QMK Firmware](https://docs.qmk.fm/)を編集して詳細なカスタマイズを行う方法

## 1. REAMPをつかう
キー配列を変更したり、LEDの点灯を変更したりするにはREMAPがあれば十分だと思います。

キーボードとPCをつないだ状態でChromeブラウザで[REMAP](https://remap-keys.app/)にアクセスして下さい。

サイトは英語表記だけですが、操作方法は直感的なので特に説明が無くても解ると思います。アカウント登録するとキーマップを保存したり読み込んだりできるので便利です。


## 2. QMK Firmwareを編集する

Ergotonic-49は、[QMK Firmware](https://docs.qmk.fm/)というオープンソースとして有志で開発されているファームウェアを利用しいています。

ロータリーエンコーダーの動作やCAPS LOCKやNUM LOCKの状態でLEDの表示を変更するような独自の動きはQMKの中で定義しています。

もしロータリーエンコーダーの動作を変更したいと考えたときはQMKのソースコードを編集する必要が出てきます。(REMAPではロータリーエンコーダーの設定を行うことができないので)

QMKにはとても沢山の機能が用意されていて、より自由な設定を行うことができます。
しかしそのためにはプログラミング言語(C言語)やPC上での黒い画面(コンソール)でコマンドを使ったコンパイル操作を行う必要があります。

Ergotonic-49のファームウェアは [ここ](https://github.com/hanachi-ap/qmk_firmware/tree/ergotonic49/keyboards/ergotonic49)から参照できるので、もしこれを見て行けそうだ! と感じたらぜひQMK Firmwareのカスタマイズに挑戦してみて下さい。
注目ポイントは [このファイル](https://github.com/hanachi-ap/qmk_firmware/blob/ergotonic49/keyboards/ergotonic49/keymaps/default/keymap.c)です。

----
 [Index](index.md)