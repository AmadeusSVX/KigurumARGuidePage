# KigurumAR
- 着ぐるみのようにVRMアバターを身に着けて、いつでもどこでも気軽に静止画、動画を撮影できるアプリです。
- リアルの被写体の人の姿はカメラの視界から消去され、代わりに人と同じ動きをするVRMアバターがリアルタイムに表示されます。
- Apple製のA12プロセッサ以降を搭載したiOSデバイス（iPhone/iPad）に対応しています。

## [「KigurumAR」をApp Storeで](https://apps.apple.com/jp/app/xxxxxxxx)

## 機能紹介
### VRMモデル読込
VRMフォーマットに準拠した任意のモデルを読み込んで、3Dアバターとして使用する事が出来ます。

[VRMフォーマットについて](https://vrm.dev/)

### 3Dポーズトラッキング
カメラの視界に入った人物のポーズ（手足の角度）を認識して、3Dアバターに反映させることができます

### 人物消去、フェードイン/アウト
カメラの視界に入った人物は、ポーズを認識されると同時に消去されて背景と同化するよう処理され、人物の姿を3Dアバターに置き換える事が出来ます。
この消去処理は人物<-->3Dアバター間でフェードイン、フェードアウトさせることができ「変身」の演出を動画で行うことも出来ます。

**綺麗に人物消去を行うには、被写体、撮影の双方に注意するべき点があります。詳しくは使い方を参照ください**

### リップシンク
表示された3Dアバターは、入力される音声によってリップシンク（口パク）を行わせることができます。
リップシンク機能の実装には凹み氏のuLipSyncを使用させていただいています。

### 床面認識


### 表情、手

### キーボードショートカット

-----

## 実行環境
Apple製のA12プロセッサ以降を搭載したiOSデバイス
- [x] iPhone 12 Pro Max
- [ ] iPhone 11 Pro
- [ ] iPhone 11
- [ ] iPhone 11 Pro Max
- [ ] iPhone 11 Pro
- [ ] iPhone 11
- [ ] iPhone XS Max
- [ ] iPhone XS
- [ ] iPhone XR
- [ ] iPad Pro 12.9 インチ (第 4 世代)
- [ ] iPad Pro 12.9 インチ (第 3 世代)
- [ ] iPad Pro 11 インチ (第 2 世代)
- [ ] iPad Pro 11 インチ

- [x] 動作確認済み

[参考ページ(英語)](https://developer.apple.com/augmented-reality/arkit/)

-----

## 使い方



## 今後の予定
- [ ] セルフタイマー追加
- [ ] 横位置での撮影対応
- [ ] 人物消去の品質改善
- [ ] iOS多機種対応
- [ ] Android版リリース

## 更新履歴
- 2021/03/xx v0.9.0公開

## お問い合わせ
- [お問い合わせページ](https://docs.google.com/forms/d/e/1FAIpQLSeM6epPLYCkLF4ngk_GQKEzkqP9Fn1FzsuyhnKS3RJylz_Klg/viewform)
- [Twitter](https://twitter.com/AmadeusSVX)


<a href="https://twitter.com/share?ref_src=twsrc%5Etfw&hashtags=Emosign" class="twitter-share-button" data-show-count="false">Tweet</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
