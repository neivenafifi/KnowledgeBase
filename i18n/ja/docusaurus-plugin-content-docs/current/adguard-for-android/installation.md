---
title: インストール方法
sidebar_position: 2
---

## 動作環境

**OSバージョン**: Android 5.0以上

**RAM**: 2 GB以上

**ディスクの空き容量**: 120 Mb

## AdGuard for Android のインストール方法

【AdGuardがGoogle Playにない理由】これは、Googleがネットワークレベルの広告ブロッカー（つまり、他のアプリの広告をブロックするアプリ）のGoogle Playでの配布を禁止しているためです。 Googleの制限的なポリシーについては、[私たちのブログ記事](https://blog.adguard.com/en/google-removes-adguard-android-app-google-play/)でご確認いただけます。

この理由で、AdGuard for Androidは直接AdGuardウェブサイトから手動でインストールする必要があります。 方法は以下の通りです。

まず、デバイスのOS設定で提供元不明のアプリケーションのインストールを許可する必要があります:

* For Android 8+: start downloading [AdGuard apk](https://adguard.com/download.html?auto=1) (see the next step), you'll be prompted to allow permission. ブラウザからのインストールが許可されていない場合は通知が表示され、 [**設定**]→[**この提供元を許可する**]→戻る→[インストール]　 でインストールが完了します。
* 【Android 7の場合】お使いのデバイスで「**設定**」→「**セキュリティ**」より「提供元不明のアプリ」をタップしてトグルをONにする。 【Android 6の場合】[**設定**]を開き、[システムとデバイス]から[その他の設定]を選択。[セキュリティ]の[提供元不明のアプリ]をオンにし、システム警告ウィンドウが開きましたらOKをタップ。 ※端末によって少し手順と項目が異なる場合があります。

![提供元不明のアプリをインストールする *mobile](https://cdn.adguard.com/public/Adguard/kb/installation/Android/ja/d1.jpg)

* 【Android 5の場合】[**設定**]を開き、**パーソナル**セクションにある[**セキュリティ**]を選択。 [**提供元不明のアプリ**]をオンにし、システムの警告ウィンドウが開きましたら[**OK**]をタップ。

![提供元不明のアプリをインストールする *mobile](https://cdn.adguard.com/public/Adguard/kb/installation/Android/ja/d1.jpg)

これで、アプリをデバイスにインストールすることができます。 ブラウザで[https://adguard.com/apk](https://adguard.com/apk)を開くか、以下のQRコードをスキャンしてください:

![QRコード *mobile](https://cdn.adguard.com/content/kb/ad_blocker/android/installation/qr.png)

ダウンロードしたファイルを保存するリクエストが表示されたら、 **OK**を押します。

![ファイルを保存する *mobile](https://cdn.adtidy.org/content/kb/ad_blocker/android/installation/save_the_file.png)

ダウンロードが完了すると、AdGuardアプリケーションをインストールするかどうかをシステム尋ねられます。 **インストール**を押します。

![インストール *mobile_border](https://cdn.adguard.com/public/Adguard/kb/installation/Android/ja/d4.jpg)

アプリを起動しますと、**EULA**とAdGuardの**プライバシーポリシー**の同意画面が表示されます。 また、2つのチェックボックスにチェックを入れることで、AdGuardの開発にご協力いただけます。 （協力される場合、「*AdGuardに自動クラッシュレポートを送信する*」と 「*テクニカル情報とインタラクション情報を送信する*」にチェックを入れてください。） 次に、「**同意する**」を押してください。

![プライバシーポリシー *mobile_border](https://cdn.adguard.com/public/Adguard/kb/installation/Android/ja/2.jpg)

**クイック設定** と **詳細な設定** のどちらかを選びます（詳細な設定も基本的にすぐに終わるので、おすすめです）。

![セットアップ *mobile_border](https://cdn.adguard.com/public/Adguard/kb/installation/Android/ja/3.jpg)

詳細な設定を選ぶと、ニーズに合わせてAdGuardを設定する流れが開始されます。 まず、検索広告をブロックするかしないかという設定です:

![検索広告に対する設定 *mobile_border](https://cdn.adguard.com/public/Adguard/kb/installation/Android/ja/5.jpg)

次に、SNSウィジェット（普通のウェブサイトで出てくるいいね！やシェアボタンなど）をブロックするかしないかという設定です:

![SNSウィジェット設定 *mobile_border](https://cdn.adguard.com/public/Adguard/kb/installation/Android/ja/6.jpg)

迷惑要素（クッキー通知、アシスタントウィンドウなど）をブロックするかしないかという設定です:

![迷惑要素設定 *mobile_border](https://cdn.adguard.com/public/Adguard/kb/installation/Android/ja/7.jpg)

次に、YouTubeアプリから広告なしで動画を閲覧する方法についての説明があり、方法をご確認いただいて次に進むだけです。

![YouTubeでの広告なし閲覧方法 *mobile_border](https://cdn.adguard.com/public/Adguard/kb/installation/Android/ja/youtube.jpg)

プライバシー設定では、ご希望の個人情報追跡からの保護レベルをお選びください:

![プライバシー保護設定 *mobile_border](https://cdn.adguard.com/public/Adguard/kb/installation/Android/ja/8.jpg)

セキュリティは、危険なサイトにアクセスしようとする時に、警告を表示するかしないかという設定です。

![セキュリティ設定 *mobile_border](https://cdn.adguard.com/public/Adguard/kb/installation/Android/ja/9.jpg)

このステップは結構重要です。 HTTPSフィルタリングで最高の広告ブロック品質を実現するために、オンにすることをお勧めします。

![HTTPSフィルタリング *mobile_border](https://cdn.adtidy.org/content/kb/ad_blocker/android/installation/10.png)

最終ステップはローカルVPNを作成することです:

![ローカルVPN構築 *mobile_border](https://cdn.adguard.com/public/Adguard/kb/installation/Android/ja/4.jpg)

これで、AdGuardのインストールは完了です。

## АdGuardのアンインストールや再インストール

モバイルデバイスにAdGuardを再インストールする必要がある場合は、 まず**設定**を開き、 **インストールされたアプリ**（Android 6）、**アプリ**（Android 5および7）、**アプリと通知**（Android 8+）、アプリ（Android 9+）を選択し、 インストールされているアプリのリストで**AdGuard**を見つけ、**削除する**を押します。

![AdGuardを再インストール *mobile_border](https://cdn.adtidy.org/content/kb/ad_blocker/android/installation/12.png)

AdGuardアプリを再インストールするには、「インストール方法」の手順を繰り返してください。