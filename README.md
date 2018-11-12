# test_1

マージリクエスト　テスト



## テスト環境

OpenCVインストールパス：C:\devel\lib\opencv\

ビルド環境：Visual Studio Community 2017

### ビルドから実行までの手順

1. ocv_test\ocv_test.slnを選択してVisual Studio 2017を起動する
2. F5(またはメインメニューの[デバッグ]->[デバッグの開始])

この操作でレッサーパンダの画像が表示されたらOKです。

終了するには適当なボタンを押すか、Visual Studio側でShift + F5を押して下さい(こっちがVS標準操作)

### プロジェクト主要設定メモ

- PATH(opencv_world*.dll用)

  - C:\devel\lib\opencv\build\x64\vc15\bin

- [C/C++]→[全般]→[追加のインクルードディレクトリ]

  - C:\devel\lib\opencv\build\include\

- [リンカー]→[全般]→[追加のライブラリディレクトリ]

  - C:\devel\lib\opencv\build\x64\vc15\lib\

- [リンカー]→[入力]→[追加の依存ファイル]

  - [Debug]C:\devel\lib\opencv\build\x64\vc15\lib\opencv_world343d.lib

  - [Release]C:\devel\lib\opencv\build\x64\vc15\lib\opencv_world343.lib
