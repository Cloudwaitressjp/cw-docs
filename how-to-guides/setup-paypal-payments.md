---
description: 簡単な設定方法で、ご自身のPayPalアカウントを使用してオンラインでの支払いを受け付ける方法をご紹介します。
---

# PayPalでのお支払いを設定する

PayPalは最も広く利用されているオンライン決済方法の一つです。CloudWaitressでは、PayPalのRESTエクスプレスチェックアウト決済機能を利用しています。これにより、お客様に代わってお支払いを処理し、お客様の口座に直接送金することができます。PayPalは一部の国と通貨でしかご利用いただけませんのでご注意ください。[こちら](www.paypal.jp)で見ることができます

{% hint style="danger" %}
オンラインでの支払いにはPayPalの代わりにStripeを使用することを強くお勧めします。PayPalは時折、私たちの経験上、様々なサービスの問題を抱えています。以下では、代わりにどのようにStripeの支払いガイドを参照してください。
{% endhint %}

{% page-ref page="setup-stripe-payments.md" %}

PayPalでの支払いの仕組み

PayPalを有効にすると、注文のチェックアウト時にオプションが利用できるようになります。選択すると、PayPalアカウントにログインしてアカウントを作成するか、クレジットカードを使用して支払いを完了するためにゲストとしてチェックアウトすることができます。

必要条件

ICloudWaitressでPayPalを使用するには、完全に有効なビジネスアカウントが必要です。すでにPayPalのビジネスアカウントをお持ちの場合は、このステップをスキップすることができます。

まだお持ちでない場合は、[https://www.paypal.com/webapps/mpp/account-selection](https://www.paypal.com/webapps/mpp/account-selection) でサインアップしてください。また、アカウント設定から個人アカウントをビジネスアカウントにアップグレードすることもできます。

PayPalアカウントの接続

REST APIアプリケーションの作成

1. [https://developer.paypal.com/developer/applications/](https://developer.paypal.com/developer/applications/) をご覧ください。 ログインボタンを使用してPayPalアカウントにログインします。 ログインしたら、"REST APIのアプリ "というタイトルが表示されるまで下にスクロールします。 アプリ作成」ボタンを押す アプリ名にビジネス名を入力し、サンドボックスの開発者アカウントフィールドを無視します。 アプリを作成」ボタンを押して、このステップを完了します。

![PayPal REST apps](https://storage.crisp.chat/users/helpdesk/website/e903fdb8557a9800/image_141scma.png)

ライブ申請資格情報のコピー

1. アプリケーションを作成した後、認証情報をコピーするページに移動します。
2.  右上のボタンを使用して、「サンドボックス」から「ライブ」ビューに変更します。
3.  下にスクロールして「シークレット」の下にある「表示」を押します。
4.  これで「クライアントID」と「シークレット」のキーが表示されます。
5.  別のウィンドウで、あなたのレストランのダッシュボードに移動し、"設定&gt;支払い&gt;PayPal "へ PayPalでの支払いを有効にし、
6. PayPalのダッシュボードから「クライアントID」と「シークレット」キーを貼り付けます。 お支払い通貨を選択し、フォームを保存します。

![PayPal application credentials](https://storage.crisp.chat/users/helpdesk/website/e903fdb8557a9800/image_1g9uc8i.png)

ペイパルの手数料

PayPalを使用して、他のオンラインクレジットカード処理業者と同様に、すべてのトランザクションに手数料が課金されることに注意してください。これは、私たちはこれについて責任を負いませんので、これはあなた自身のPayPalアカウントを介して自分で管理する必要があります。お客様は、PayPalのウェブサイトを使用して、それぞれの国と通貨の手数料を確認することができます。

払い戻し

現在のところ、返金はPayPalアカウント内から手動で処理する必要があります。

