# 🧸 PY32F002Aマイコン搭載 電子オルゴールプロジェクト (PUYA_orgel_SW_BTL)

安価でコストパフォーマンスに優れたPUYA半導体製マイコン「PY32F002A」を使用した、おもちゃ修理・マイコン換装用の電子オルゴールプロジェクトです。外部メモリによる音声再生をあえて実装しない構成により、省スペースと低コスト化を追求しています。

---

### 🛠️ 現役ドクターの皆様へ：修理報告・カルテ募集中！
本プログラム（PUYA_orgel シリーズ）を活用し、おもちゃのマイコン換装やオルゴール化による修理（蘇生）に成功しましたら、ぜひ知見をご共有ください！
皆様が残した1つのカルテが、全国の同志の「次の臨床」を支える大きな力になります。

#### 👉 **[おもちゃ修理・マイコン換装 報告フォームからカルテを投稿する](https://github.com/ToyDr-W/PUYA_orgel_SW_BTL/issues)**
（Issues画面右上の「New issue」ボタンをクリックし、報告フォームを選択）
<p align="center">
<br>
  <a href="https://youtu.be/nDzyxNxgCoU?si=-bdgiRvxjjMFzNJV">
 <img src="https://github.com/user-attachments/assets/65468f8d-1609-4c43-92fb-1ea15366466a" alt="260930_prototype" width="45%">
 <br>
    <em>▶️ YouTubeで動作確認動画を再生する</em>
  </a>
</p>

---

## 🛠️ 対象プロジェクト（2モデル）

マイコンのPWM出力を活用したBTL駆動に対応する2つのモデルを内蔵しています。

* **`orgel_SW_F002A_8_BTL`**: 省スペースな8ピンパッケージを使用し、スイッチ切り替えとBTL駆動を両立した小型おもちゃ向けモデル。
* **`orgel_SW_F002A_16_BTL`**: 16ピンパッケージを使用し、複数スイッチやセンサー制御、LED演出などを追加しやすい拡張性の高いモデル。


> [!NOTE]
> ### 📥 最新データのダウンロードについて（v1.2.0正式リリースまで）
> 開発元（名張市つつじが丘おもちゃ病院様）の公開ダウンロードファイルは随時更新されます。次のアップデートがあったときは、本リポジトリへの反映は しばらく様子を見て、安定後に **v1.2.0（安定版）** としてリリース予定です。
> 
> それまでの間、最新の回路図およびプログラム一式をダウンロードするには、
> [ここをクリックしてください。 ⬇️](https://github.com/ToyDr-W/PUYA_orgel_SW_BTL/archive/refs/heads/main.zip)
> ダウンロード（9.0 MBのZIPファイル）が直ちに開始されます。
>
> ---
>
> ### 📥 Downloading the Latest Data (Prior to v1.2.0 Official Release)
> The file made available for download by the developer (Nabari City Tsutsujigaoka Toy Hospital) is updated periodically. When a new update is released, it will not be immediately incorporated into this repository; instead, we will monitor it for a while, and once it has proven stable, we plan to release it as **v1.2.0 (stable version)**.
> 
> In the meantime, [please click here to download ⬇️](https://github.com/ToyDr-W/PUYA_orgel_SW_BTL/archive/refs/heads/main.zip) the latest circuit diagrams and the complete set of programs. The download (9.0 MB ZIP file) will begin immediately.
> 

---

## 🎵 本プロジェクトの特徴と魅力

### 🌟 おもちゃ修理への応用
開発者である「名張市つつじが丘おもちゃ病院」さまのブログでは、電源条件や曲選択、周辺制御など多岐にわたるカスタマイズに対応するファームウェア開発スキルの重要性が述べられており、本プロジェクトはその実践的なベースとして活用いただけます。詳細は該当ブログもご参照ください。

### 🎹 約180曲の楽曲群と表現力
* 童謡からクラシックまで約180曲から選択可能で、情操教育にも最適です。
* エンベロープやエフェクト制御により、豊かなオルゴール音を奏でます。

### 📐 基板レイアウトの練習
ブレッドボード解説を省き、実際の基板パターン設計の実践に特化しています。

---

## 📂 フォルダ構成について

フォルダ構成を一段深めて階層化し、GitHub上での視認性とアクセス性を大幅に向上させています。

---

## 📖 詳しい解説・回路図（Wikiページ）

回路図やカスタマイズ方法などの詳細は、専用の Wiki ページをご確認ください。

👉 [📖 PUYA電子オルゴール解説・回路図（Wikiページ）へ移動する](https://github.com/ToyDr-W/PUYA_orgel_SW_BTL/wiki)

---

## 🤝 地域貢献とリサイクルへの想い
おもちゃのリサイクル活動にお役立てください。
