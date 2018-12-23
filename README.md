# 職務経歴書

|key|value|
|---|-----|
|Name|中林智之|
|GitHub|[tomoyuki-nakabayashi](https://github.com/tomoyuki-nakabayashi)|
|Speaker Deck|[tomoyuki](https://speakerdeck.com/tomoyuki)|
|Qiita|[tomoyuki-nakabayashi \- Qiita](https://qiita.com/tomoyuki-nakabayashi)|
|Blog|[低レイヤ強くなりたい組込み屋さんのブログ](https://tomo-wait-for-it-yuki.hatenablog.com/)|
|Twitter|[@LDScell](https://twitter.com/LDScell)|

## 学歴

### 計算機アーキテクチャ研究室所属生 (2008 - 2014)

三重大学工学研究科システム工学専攻　博士後期課程修了

[博士論文 \[Reserches on fabrication of low-energy heterogeneous multi-core processors\]](http://www.arch.info.mie-u.ac.jp/project/GradThesis//db/100003.pdf)

低電力プロセッサの設計と実装を主軸とした研究に従事。

- 研究テーマ
  - 低消費電力プロセッサアーキテクチャ (可変段数パイプラインアーキテクチャ)
  - 低電力D-flip-flop
  - Single-ISA Heterogeneous Multi-core Processor
  - プロセッサ向けRTL/C co-simulation framework

- 技術
  - プロセッサアーキテクチャ (パイプライン、スーパースカラ)
  - Verilog/SystemVerilog
  - RTL/C協調シミュレーション
  - LSI設計 (論理合成、配置配線、各工程ごとのシミュレーション)
  - LSIのテスト
  - 電子回路設計 (SPICEシミュレーション、スタンダードセルの物理レイアウト設計)
  - MIPS64, Alpha 21264アセンブラ

研究成果で見ると、あまり冴えない博士課程であった。
これは、LSI実装に拘り、過度に実装に重きを置いたためであると考えている。そのおかげで、とにかく泥臭いエンジニアリングを行うことになった。
配置配線ツールで解消しきれないDRCエラーを手動で取り除いたり、試作したLSIをLSIテスターでテストしたり、テスト用のボードを自作したり、ロジックアナライザを利用する経験ができた、という良いところもあった。

博士課程に進んだものの、研究者には向いていなさそうだったため、手を動かせそうな企業へと就職した。
プロセッサを学んだので、次はOSを学ぼう、とりあえずLinuxできるところ、という割と安易な発想で、現職を選択した。

## 職務履歴

### 某中堅SIer 組込み事業部 (2014/4 - )

組込みLinux/Androidを中心としたエンジニアリングを経験。

#### ヘッドマウントディスプレイ向けAndroidカスタマイズ (2014/8 - 2016/6)

カメラ/Wi-Fi/Bluetoothの機能を受託開発。チームメンバーは、PM/PL/自分の3人。
カスタムボードの新規搭載デバイスに対して、driver組込み、および、製品仕様を満たさないdriverへの対応を実施。

|key|value|
|---|-----|
| SoC | OMAP4 |
| OS | Android 4.0 |

- 技術要素
  - Linux device driver 組込み / カスタマイズ / 不具合修正
    - Camera (V4L2/OMAP4 ISS) / Wi-Fi / Bluetooth (HFP) / Power management
  - Androidカスタマイズ
    - HAL / JNI / Java API拡張
    - テストアプリケーション作成
- その他
  - Camera機能はファームウェアを担当する海外ベンダと協力しながら開発

Cameraでは、Linux driverが存在していないデバイスであったため、既存物をベースに、driverを作成した。
Wi-Fiでは、driverが対象のLinux kernel versionに対応しておらず(kernelが古すぎるため)、一部機能が動作していない原因を解析し、upstreamからbackportすることで解決した。
Bluetoothでは、DMA bufferをダンプしたり、オシロスコープで最終出力をプローブすることで、問題を絞り込み、解決へと導いた。

各対応ともに短納期であったため、効果的に問題を絞り込む方法や、エスカレーションという手段を学んだ。

#### ドライブレコード先行試作開発 (2016/7 - 2016/9, 2017/5 - 2017/7)

第一期ではYoctoを利用した組込みLinux PFの構築およびサンプルアプリケーションの実装を担当した。第二期では、顧客へのLinux/OSSを活用する開発方法のレクチャーおよびクラウド連携サンプルアプリケーションを担当した。チームメンバーは、PM兼PLと自分の2人。

|key|value|
|---|-----|
| SoC | i.MX6 solo |
| OS | Linux 3.14 |

- 技術要素
  - Yocto
  - gstreamer
  - Bluemix (現IBM Cloud)
    - MQTT / BLE / NodeRED / HTTP / JavaScript / Dockerを軽く

