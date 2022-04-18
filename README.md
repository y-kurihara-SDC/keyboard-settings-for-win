## 概要

**Happy Hacking Keyboardキーマップ変更ツールとAutoHotkeyを使用しで、HHKBでMacのUS配列キーボード使用時と同じキー操作を可能にします。**

左右 Cmd キーの空打ちで IME を OFF/ON する

* 左 CMD キーの空打ちで IME を「英数」に切り替え
* 右 CMD キーの空打ちで IME を「かな」に切り替え
* CMD キーを押している間に他のキーを打つと通常の CMD キーとして動作

* Emacs配列への対応
    上下左右移動やctrl + k等

Happy Hacking Keyboardキーマップ変更ツール
  - LCMDへRCtrl, RCMDへLCtrl、CtrlへRCtrlを割当て

AutoHotkey
  - RCMD(LCtrl)+p,n,b,f等でemacs配列へ対応
  - 同時にLCMD(RCtrl)+c等で既存のWindowsのコピー処理等が行える


## 動作環境

* Windows10

## 使い方
以下のURLからHappy Hacking Keyboardキーマップ変更ツールをインストールします。
https://happyhackingkb.com/jp/download/

ツールを起動し、HHKB_Setting.hksから設定を読み込み、HHKBへ反映します。

ctrl-ime-ahk.zip をダウンロードして解凍し、ctrl-ime-ahk.exe を好きな場所に置き、起動してください。 タスクトレイに常駐します。

その後、ctrl-ime-ahk.ahkを実行しカスタマイズした設定を反映させてください。

終了する場合はタスクトレイのアイコンを右クリックし、「終了」をクリックしてください。

アンインストールは ctrl-ime-ahk.exe を削除するだけで OK です。

## 既知の不具合

* Aキー横のCtrlキーに割り当てられているRCtrlキーであり、Aキー横のCtrlキーの単独押下でIMEがONになる。

## 参考

[Altの空打ちで日本語入力(IME)を切り替えるツールを作った](http://www.karakaram.com/alt-ime-on-off/)

