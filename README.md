# AIP

**AIP 公式配布リポジトリ**

AIPは、SNS投稿・企画・分析などをAIで支援するWindows向けデスクトップアプリケーションです。

このリポジトリは、STARTLINEが提供する **AIP公式インストーラーの配布専用リポジトリ** です。

AIPのソースコードはこのリポジトリでは公開していません。

---

## Download

最新版のAIPはこちらからダウンロードできます。

[最新版 AIP-Setup.exe をダウンロード](../../releases/latest/download/AIP-Setup.exe)

### 対応OS

* Windows 11
* Windows 10

### 料金

AIP本体は無料で利用できます。

一部の追加機能・プラグインは別途ライセンスが必要な場合があります。

---

## Install

1. `AIP-Setup.exe` をダウンロードします。
2. ダウンロードしたファイルを実行します。
3. 画面の案内に従ってインストールします。
4. インストール完了後、AIPを起動します。

AIPは複数の内部コンポーネントから構成されていますが、必要なファイルはインストーラーによって自動的に配置されます。

個別のファイル操作は必要ありません。

---

## Update

AIPにはアプリケーション内の自動アップデート機能があります。

通常はAIPから更新を実行してください。

### 手動アップデート

自動アップデートが利用できない場合や、AIPを最新版へ再インストールしたい場合は、このリポジトリから最新版の `AIP-Setup.exe` をダウンロードして実行してください。

既にAIPがインストールされている場合は、既存環境を認識して更新インストールを行います。

[最新版をダウンロード](../../releases/latest/download/AIP-Setup.exe)

---

## Repair / Reinstall

AIPのプログラムファイルに問題が発生した場合も、最新版の `AIP-Setup.exe` を再実行することで再インストールできます。

通常の再インストール・手動アップデートでは、AIPのユーザー設定や利用データを保持する設計です。

---

## Release Information

各バージョンの更新内容は [Releases](../../releases) から確認できます。

正式リリースには原則として以下を掲載します。

```text
AIP-Setup.exe
SHA256SUMS.txt
```

`SHA256SUMS.txt` を使用して、ダウンロードしたインストーラーの整合性を確認できます。

---

## Official Website

AIP公式サイト

https://aip.snstart.work/

AIPを初めて利用する場合は、公式サイトからのダウンロードを推奨します。

---

## Security

AIPはSTARTLINE公式サイトおよび本GitHubリポジトリから配布します。

第三者サイトなどから配布されているAIPインストーラーについては、STARTLINEでは正当性を保証できません。

最新版は必ず公式サイトまたは本リポジトリから取得してください。

---

## Source Code

このリポジトリはAIPのバイナリ配布専用です。

AIP本体のソースコード、内部設計、ビルド環境およびライセンス管理基盤のソースコードは公開していません。

---

## Publisher

**STARTLINE**

AIP Official Distribution Repository

© STARTLINE
