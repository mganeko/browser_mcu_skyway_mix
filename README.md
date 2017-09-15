# Browser MCU Skyway Mix

* Video/Audio mixing sample for [Skyway](https://webrtc.ecl.ntt.com/en/), using [Browser MCU Core](https://github.com/mganeko/browser_mcu_core) library 
* --
* [Browser MCU Core](https://github.com/mganeko/browser_mcu_core) ライブラリを利用した、[Skyway](https://webrtc.ecl.ntt.com)向けの映像/音声合成サンプルです

## Confirmed Environment / 動作確認環境

* Server OS
  * Mac OS X 10.12.5
  * Ubuntu 16.04 LTS
* Web Browser
  * Chrome  58.0.3029.110 (64-bit) for MacOS X
  * Firefox 54.04 (64-bit) for MacOS X
* Skyway Community Edition (2017.09) 

## Preparation / 準備

#### Install / インストール

```
git clone --recursive https://github.com/mganeko/browser_mcu_skyway_mix.git
```

setup in your own web server / Webサーバー上に配置してください


#### Try on GitHub pages / GitHub pages で試す

* try GitHub pages / GitHub pages で試す
  * Please allow mganeko.github.io for you API Key / ご利用のAPI Key にmganeko.github.io からのアクセスを許可してください
  * https://mganeko.github.io/browser_mcu_skyway_mix/mix.html


## How to Use / 使い方

* Skyway に登録し、API Key を取得してください。
* 併せて、自分のサーバーのドメインを、Skywayの利用ドメインに設定してください。
* index.html をChrome/Firefoxで複数開き、それぞれ同じAPIキー指定してください
* [Start Video] --> [Connect] で Skywayによる通話を開始してください
* mix.html をChromeで開き、APIキー指定してください
* [Connect]ボタンで接続、映像/音声合成を開始します
* [Start Record]で録画開始、[Stop Record]で録画を終了します
* [Downlaod]のリンクから、録画したファイルを保存できます

#### NOTE / 注意

* mixed video will not be updated when window/tab is hidden
  * In headless browser, this is not a restriction
* mixのウィンドウ/タブが完全に隠れていると、合成した映像が更新されません
  * ヘッドレスブラウザの場合は、画面が見えなくても問題ありません

## License / ライセンス

* Browser MCU Skyway Mix is under the MIT license
* Browser MCU Skyway Mix はMITランセンスで提供されます

