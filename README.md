# 職務経歴書

|Name|中林智之|
|---|-----|
|GitHub|[tomoyuki-nakabayashi](https://github.com/tomoyuki-nakabayashi)|
|Speaker Deck|[tomoyuki](https://speakerdeck.com/tomoyuki)|
|Qiita|[tomoyuki-nakabayashi \- Qiita](https://qiita.com/tomoyuki-nakabayashi)|
|Blog|[低レイヤ強くなりたい組込み屋さんのブログ](https://tomo-wait-for-it-yuki.hatenablog.com/)|
|Twitter|[@LDScell](https://twitter.com/LDScell)|
|BOOTH|[sabizen](https://sabizen.booth.pm/)|

- 寄稿
  - [インターフェース2020年5月号 ついに登場！？C/C++以外の選択肢Rustの研究](https://interface.cqpub.co.jp/magazine/202005/)

## 希望条件

### やりたいこと

- 低レイヤ技術 (プロセッサ、FPGA、Hypervisor、OS、コンパイラなど)
- 組込み (IoT系: ネットワーク/セキュリティ含む、ファームウェア/組込みLinuxどちらも可)
- 開発の改善活動
- スケールする組織づくり
- 価値を信じられる仕事

組込みでRustが使える可能性があると泣いて喜びます。

### 勤務体系希望

- 東京近郊勤務
- 子育ての時間は自宅に居たいです (6:00-7:00/18:00-20:00くらい)
  - その前後で作業するのは問題ありません

## 性格（character）

MBTIは[ESTJ](https://en.wikipedia.org/wiki/ESTJ)型で、得意なこと、苦手なことがおおよそ一致します。
問題解決、タスクベースで物事を進める時に、特に力を発揮します。また、物事の遂行にあたり、組織的に動くことも特徴的です。
進め方が強引になるときがあります。

いわゆるアイデアマンでは**ありません**。新規事業を創造する、といったフェーズでアイデアを出すメンバーとして力を発揮することはないでしょう。
課題や問題が明確になると、自律的に動きます。

### 得意なこと

- 具体的、事実実際的に物事を捉え、論理的に考え、判断すること
- 計画を立てること、その計画を効率的に遂行すること

### 苦手なこと

- 人の気持ちを第一に考えて、判断すること
- 抽象的に物事を捉えること

(改善しようと努力しています。傾向として)

## 職務履歴

### 某ベンチャー企業 (2019/2 - ) Senior Vice President of Embedded Software Development Group

エンジニアリングチーム (9名) の取りまとめ。
新しいプログラミング言語を用いた組込みシステムの開発に従事。
開発の他、PM、採用、営業、教育なども兼任しているが迷走中。

#### 組込みランタイム開発　(2019/2 - 現在)

組込みのベアメタルランタイムをスクラッチから開発中

- ホストOS上でもマイコン上でも同じアプリケーションが動作する言語ランタイム/標準ライブラリの開発
  - コンパイル時計算機能を活用したマルチプラットフォーム対応
  - async機能を活用したマルチタスク対応
- 10名/リーダー

#### 組込みボードの開発 (2019/4 - 2019/8)

ボード開発をソフトウェアの観点から支援し、試作基板の動作確認を担当

- 基板設計担当者のサポートと試作基板の動作確認
  - ボード立ち上げ
  - Zephyr (動作確認に使用)
- 4名/メンバー

#### プログラミング言語エコシステム開発 (2019/2 - 現在)

主に標準ライブラリと一部のコンパイラ機能の開発を担当

- 言語の改善、バグフィックス、ドキュメンテーション
  - コンパイラへの新機能追加の提案やプロトタイプ実装
  - コンパイラや標準ライブラリのバグフィックス
- 8名/メンバー

#### 言語の普及活動

コミュニティ運営や技術書典での書籍頒布、外部での講演、顧客へのトレーニングなど。

#### LLVM IRを対象としたぜい弱性解析ツールの開発 (- 2019/10 - 現在)

- 脆弱性解析ツールのプロトタイプを実装
  - 開発は2020/4時点でチームに引き継いでおり、現在はアドバイザ
- 4名/リーダー

### 組込み系SI企業 (2014/4 - 2019/1)

受託開発。組込みLinux/Androidを中心としたエンジニアリングを経験。

#### 次世代自動運転システムPF構築 (2018/11 - 2019/2)

FPGA搭載のSoC (Xilinx ZynqMP) を搭載した次世代自動運転システム開発の技術サポート (FPGAおよびLinux)。

- PL (FPGA) に実装するソフトロジックIPとそのLinux driver調査
  - FPGAでのプロトタイプおよびLinuxのテストプログラム作成
  - ネットワーク周り (Ethernet MAC/Distributed Switch Architecture: DSA)
- 10名/技術サポート

#### AGL リファレンスPF構築 (2018/11 - 2019/2)

Intel ApollolakeのSoCを対象に、Automotive Grade Linux (AGL) のリファレンスPFを構築

- カスタムボードの立ち上げやLinux device driverの組込みを担当
- 2名/メンバー

#### 組込み向けXen Hypervisor環境構築 (2018/9 - 2018/11)

Intel ApollolakeのSoCを対象に、組込み向けXen Hypervisor環境を構築

- Xen Hypervisorの環境を構築し、手順書を提供
- 1名/PL兼メンバー

#### FPGAにおけるRISC-Vアクセラレータの検討 (2018/7 - 2018/10)

RISC-V実装＋高位合成の組合せでシステムの高速化が可能かどうかXilinx ZynqMPを対象に検討。

- RISC-Vと高位合成で生成された回路をインテグレーションし、性能評価
- 1名/PL兼メンバー

#### 統合コックピットシステム先行試作 (2016/9 - 2018/6)

Intel ApollolakeのSoCを対象に、統合コックピットシステムの先行試作を担当。
テスト駆動開発、GitLab (GitLab CI含む)の導入、設計とコードのレビュー、C++およびQt勉強会の開催、といった活動を並行して行うようになり、チームのアウトプットの増大を目指した。

- 主にミドルウェア(Wayland / PulseAudio制御)とHMIアプリケーション(Qt)の開発を担当
  - チーム全体の開発効率改善活動
- 8名/サブリーダー

#### ドライブレコーダ先行試作 (2016/7 - 2016/9, 2017/5 - 2017/7)

第一期ではYoctoを利用した組込みLinux PF (SoCはNXP i.MX6) の構築およびgstreamerサンプルアプリケーションの実装を担当した。
第二期では、Linux device driver開発ハンズオン資料とOSSライセンス取り扱いガイドラインを作成、また、クラウド連携サンプルアプリケーションを開発し提案活動を行った。

- 組込みLinux
  - Yoctoによるビルドやgstreamerを使った録画アプリケーションの作成
- SensorTagを使ってクラウド (Bluemix) 連携するアプリケーションを作成
  - Bluemix / MQTT / BLE / NodeRED / Docker / JavaScript / HTTP などを軽く
- 2名/メンバー

#### ヘッドマウントディスプレイ向けAndroidカスタマイズ (2014/8 - 2016/6)

カメラ/Wi-Fi/Bluetoothの機能を担当。
カメラ機能では、Linux device driverを開発し、当時のAndroid Camera APIでは実現できない仕様が存在したため、HAL / JNI / Java APIを拡張する開発を行った。
Wi-Fi/Bluetoothでは、一部機能が動作していない原因を解析し、製品発売までの短期間に問題を解決した。

- Android PFの構築
  - Android 4.0 / TI OMAP4
- 3名/メンバー

## 学歴

### 計算機アーキテクチャ研究室所属 (2008 - 2014)

三重大学工学研究科システム工学専攻　博士後期課程修了

博士論文 Reserches on fabrication of low-energy heterogeneous multi-core processors

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

## 業務外/個人活動

### 組込みRust

組込みRustの普及活動をプライベートで実施中。

- ドキュメントの和訳
- 同人誌の発行
- 雑誌 (インターフェース) への寄稿

### MBTI

自己理解、他者理解のために心理学 (MBTI) を継続的に学習中。

## 言語経験

|言語|業務|業務外|
|---|---|---|
|C|5年|10年|
|C++(14)|3年|2年|
|Rust|-|3年|
|Verilog/SystemVerilog|半年|6年|
|Go|-|3ヶ月|
|Python|6ヶ月|3ヶ月|
|JavaScript|3ヶ月|3ヶ月|
