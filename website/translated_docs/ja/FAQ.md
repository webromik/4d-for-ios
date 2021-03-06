---
id: faq
title: FAQ
---

## システム要件

<details>
<summary>
    <strong>4D for iOS を使用するには，高度なスキルが求められますか</strong>
</summary>

4D for iOS を使用すれば，ネイティブ iOS アプリに関する専門的な知識がない方でも，4Dから簡単にモバイルプロジェクトが作成できます！

モバイルプロジェクトエディターは，モバイルアプリ開発について特に何も知らなくても，4D for iOSが使用できるように設計されているからです。

</details>

<details>
<summary>
<strong>4D for iOSを使用するためのシステム要件がありますか</strong>
</summary>

### バージョン対応表

| Xcode  | Swift | iOS      | 4D   | macOS   |
| ------ | ----- | -------- | ---- | ------- |
| 11.4   | 5.2   | OS 13.4  | 18.2 | 10.15.2 |
| 11.3.1 | 5.1.3 | iOS 13.3 | 18.1 | 10.14.4 |
| 11.3.1 | 5.1.3 | iOS 13.3 | 18R2 | 10.14.4 |
| 11.2   | 5.1   | iOS 13.2 | 18   | 10.14.4 |
| 10.2.1 | 5.0   | iOS 12.2 | 17R6 | 10.14.4 |
| 10.2   | 4.2.1 | iOS 12.2 | 17R5 | 10.14.3 |
| 10.1   | 4.2.1 | iOS 12   | 17R4 | 10.13.6 |
| 10.0   | 4.2   | iOS 12   | 17R3 | 10.13.6 |
| 9.4    | 4.1.2 | iOS 11.4 | 17R2 | 10.13.2 |
| 9.3.1  | 4.1   | iOS 11.3 | 17R2 | 10.13.2 |

過去バージョンの Xcode は，下記のサイトから入手することができます。 https://developer.apple.com/download/more/

=> 登録デベロッパーは，Apple Developer からプレビュー版のリリースをダウンロードすることができます。

[こちら](prerequisites.html)の情報もご覧ください。

</details>

<details>
<summary>
<strong>Windowsで 4D for iOS アプリを開発できますか。</strong>
</summary>

いいえ。 アプリケーションのコンパイルには Xcode，テストには iOS シミュレーターを使用するため，macOS 開発する必要があります。

</details>

## ライセンス

<details>
<summary>
<strong>4D for iOS を使用するためには，4D Web Server のライセンスが必要ですか</strong>
</summary>

いいえ。4D Server v17 R2 以降であれば，4D for iOS のサーバーにすることができます。

</details>

<details>
<summary>
<strong>試用版または評価ライセンスは発行していますか</strong>
</summary>

4D v17 R2 以降の 4D Developer Professional または 4D Server ライセンスがあれば，4D for iOS を使用することができます。

R バージョンが利用できる 4D のパートナープログラムに未加入，あるいはv17のライセンスに「メンテナンス」プログラムが付帯していない場合，4D v18 のライセンスで利用することができます。

</details>

<details>
<summary>
<strong>4D for iOS でアプリを開発するために必要なライセンスはどれですか</strong>
</summary>

macOS プラットフォームの 4D Developer Pro v17 R2 以降です。

</details>

<details>
<summary>
<strong>4D for iOS で作成したアプリを配付するために必要なライセンスはどれですか</strong>
</summary>

4D for iOSアプリと同期するサーバーアプリは 4D Server（macOS または Windows）の v17 R2 以降のライセンスで運用することができます。

4D for iOS 専用のライセンスというものはありません。 4D for iOS アプリは 4D Remote（クライアント）の余剰同時接続ライセンスを消費します。

4D Server のライセンスが許す限り，Mac・Windows・iPhone デバイスから同時に接続することができます。

</details>

<details>
<summary>
<strong>4D Server にクライアント 2 接続ライセンスがインストールされている場合（合計 4 接続），何台のデバイスから接続できますか</strong>
</summary>

最大で 4 台のデバイスから接続できます。

</details>

## その他

<details>
<summary>
<strong>iOS アプリでデータベースを更新することができますか</strong>
</summary>

はい。もちろんです！

</details>

<details>
<summary>
<strong>データはどこに保存されているのでしょうか</strong>
</summary>

データは iOS デバイスのローカルデータベースに保存されています。 したがって，オフラインモードでもデータベースにアクセスすることができます。

</details>

<details>
<summary>
<strong>4D for iOS でリレーショナルデータベースを使用できますか</strong>
</summary>

はい。もちろんです！

</details>

<details>
<summary>
<strong>4D for iOS で計算フィールドを使用することができますか</strong>
</summary>

数式を公開することはできませんが，計算済みの値をフィールドに登録しておき，そのフィールドを 4D for iOS の「[ストラクチャ](structure.html)」セクションで公開することができます。

</details>

<details>
<summary>
<strong>データベースにピクチャフィールドがなくても使用できますか</strong>
</summary>

ピクチャフィールドは必須ではありませんが，最高のユーザーエクスペリエンスを実現するためには，画像を積極的に使用することが勧められています。

4D for iOS には，バラエティに富んだ[リスト画面](list-form-templates.html)および[詳細画面](detail-form-templates.html)のテンプレートが用意されています。 画像やグラフを含まない，シンプルなデザインもあります。

</details>

<details>
<summary>
<strong>iOS アプリのためにアイコンを作成する必要がありますか</strong>
</summary>

4D for iOS アプリには，オリジナルのアイコンを設定することが勧められています。特に設定しない場合，4D のロゴマークがデフォルトのアイコンとなります。

デスクトップ版アプリのアイコンがある場合，プロジェクトエディターの「[一般](general.html)」セクションのアイコンエリアにドラッグ＆ドロップするだけで，モバイル版アプリのアイコンが自動的に作成されます。

</details>

<details>
<summary>
<strong>作成したアプリはどのようにテストするのですか</strong>
</summary>

4D for iOS で作成したアプリは，[シミュレーター](simulator.html)で手早くテストすることができます。 実機の iOS デバイス（iPhone または iPad）で[テスト](install-device.html)するためには，有料の**Apple Developer アカウント**が必要です。

**注記**: 出力した iOS プロジェクトを Xcode で開けば，無料の**Apple Developer アカウント**でもアプリをインストールすることができます。

</details>

<details>
<summary>
<strong>iPhone と iPad 用に別々の iOS テンプレートを作成する必要がありますか</strong>
</summary>

4D for iOS に用意されているテンプレートは，すべて iPhone 用に最適化されています。 しかし，iPad でも使用することができます。

</details>

<details>
<summary>
     <strong>Apple Developer のアカウントが必要ですか</strong>
</summary>

4D for iOS で作成したアプリをテストするためには，最低限でも無料の [Apple Developer アカウント](free-developer-account.html) が必要です。

4D for iOS で作成したアプリを配付するためには， [Apple Developer Enterprise Program](register-apple-developer-enterprise-program.html) （インハウス配付）または [Apple Developer Program](register-apple-developer-program-organization.html) （App Store 配付）に加入することが必要です。

</details>

<details>
<summary>
<strong>4D for iOS で作成したアプリをカスタマイズすることができますか</strong>
</summary>

4D for iOS は，標準の Xcode プロジェクトを出力しますので，必要であれば，[ Xcode で開いて編集する](open-xcode.html) ことができます。

</details>