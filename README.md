# basic_system

## KAWAII Quest \~ルンバの大冒険\~

## Things necessary
- 写真を撮る x1~
    - ルンバ
    - kinect
    - RaspberryPi
    - 360度カメラ

- サーバ
    - RaspberryPi x複数

## What's service?
- ルンバはAutoモードとUserモードがある．
    - Autoモード
        - ルンバは自動で動き，可愛いものを見つける

    - Userモード : 教師データの収集
        - ルンバを操作し，可愛いものを探す
        - ルンバの操作はブラウザから見ることができる

## What shoud we do?
- キネクトの動画をブラウザに映す
- ルンバから画像の転送(キネクト or 360カメラ)
- 可愛いものの検知 -> ディープラーニング
- ブラウザからルンバの制御(進む/旋回/カメラの操作)/画像の選択(取られた画像が可愛いかどうか)/どのルンバを操作するか

## Memo
- Movie is lot of picture.
- So I use Rails
