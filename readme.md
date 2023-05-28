# Keyball series

## About

keyball61の自分用ファームウェア

以下に対応

* Keyboard Quantizerに繋ぐと両方スレーブになってしまうので`MASTER_LEFT`にしてしまう。
* `SAFE_RANGE`がずれていたので、オレオレセーフレンジに書き換え。
  * 0x5EA5を起点とする。
* LCDにレイヤ情報、モディファイアキー情報を表示する。
* CPI/Scroll除数変更をShiftキー同時押しで反転できるように変更。

## 参照

[keyballのための はじめてのQMK firmware環境構築 Mac編](https://note.com/yinouet1001/n/n856b45220ad4)

[goropikariの備忘録 keyball39 を組み立てた 検証2: MASTER_LEFT で固定してしまう](https://goropikari.hatenablog.com/entry/keyball39_build_log#検証2-MASTER_LEFT-で固定してしまう)

## キーボード情報

<https://github.com/Yowkees/keyball>

<https://github.com/Yowkees/keyball/tree/main/qmk_firmware/keyboards/keyball>
