## 🌱 はじめに

DartPadという公式のオンラインIDEを使って、国旗を表示するアプリを作っていきましょう！
DartPadはこちら！ → https://dartpad.dev

## :tada: 今回のゴール

- DartPad で Dart と Flutter のプログラムを実行できるようになること
- Widget が何かを理解できること
- カスタム Widget が作成できること
- `Container`, `Column`, `Row` の使い方を理解できること 

終了時にこれらを達成できていれば完璧です！
頑張っていきましょう。

## 1. Flutter と DartPad に触れてみよう！

国旗作りに入る前に、Flutter と DartPad について、軽くお勉強しましょう。

### :thinking: Flutterとは :thinking:

Flutter は Google が提供する、マルチプラットフォームアプリケーションを構築するためのフレームワークです。
つまり、FlutterだけでAndroid, iOS, Windows, Macなどさまざまな機器を対象としたアプリを作成することができます。

開発言語としては Dart という言語を採用しています。

### :muscle: DartPad でプログラムを動かしてみよう :muscle:

Flutter が何かわかったと思うので、ここでは、DartPad でプログラムを動かしてみましょう。

まずは、Flutterではなく、Dartのプログラムを動かしてみます。
DartPad を開いて、画面上部の「New Pad」を選択します。

![Create New Pad](./imgs/01_create_new_pad.png)

HTMLのトグルが画像のようにオフになっていることを確認して、Dartを選択します。
その後、画面左側に下記画像と同じプログラムが書かれていればOKです。

![New Dart Program](./imgs/02_new_dart_program.png)

プログラムの動かし方は簡単です。Runボタンを押してみましょう。これだけで実行できます。
hello 1 から hello 5まで出力できたらOKです。

![Dart Program Result](./imgs/03_dart_program_result.png)

---

同じように、Flutterのプログラムを動かしてみましょう！
New Pad から今度は Flutter を選択します。右側の欄がUI Output に変わっていればOKです。

![UI Output](./imgs/04_ui_output.png)

