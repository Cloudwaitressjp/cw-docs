---
description: Facebookでの注文を有効にすることで、あなたの顧客があなたのFacebookページから注文できるようになります。
---

# Facebook注文の設定

{% hint style="danger" %}
この機能は素晴らしいと思うと同時に、Facebookを通じて注文する人にとっては正直あまり快適ではありません。また、これらのタブは、Facebookのデスクトップ版でしか利用できないため、さらに制限されています。つまり、携帯電話のユーザーには使えないということです。Facebookはまた、定期的に変更を行い、時には物事が予期せず壊れることがあります。このように、全体的にはこの機能の使用をお勧めしません。単にあなたの注文ドメインに人々を送るだけの方がはるかに信頼性の高いオプションです。
{% endhint %}

[https://developers.facebook.com](https://developers.facebook.com) をご覧ください。まだFacebookにサインインしていない場合は、通常のFacebookアカウントでサインインすることができます。

完了したら、右上の「マイアプリ」ボタンを選択し、「新規アプリの作成」を選択します。

![](https://storage.crisp.chat/users/helpdesk/website/e903fdb8557a9800/image_f92n5y.png)

アプリ名のビジネス名をメールアドレスと一緒に入力し、createを押します。

アプリを作成すると、アプリのダッシュボードに移動します。左メニューの "設定 &gt; 基本 "を選択します。

![](https://storage.crisp.chat/users/helpdesk/website/e903fdb8557a9800/image_wtsxiz.png)

ページタブ」を選択します。ここで、「セキュアなページタブURL」の下にストアURLを入力し、「ページタブ名」の下にページタブと呼びたいものを入力する必要があります。ストアURLは「[https://yourdomain.cloudwaitress.com」のようなCloudWaitressのサブドメインか、設定されている場合はカスタムドメイン名にすることができます。](https://yourdomain.cloudwaitress.com」のようなCloudWaitressのサブドメインか、設定されている場合はカスタムドメイン名にすることができます。)

![](https://storage.crisp.chat/users/helpdesk/website/e903fdb8557a9800/image_cb565a.png)

あなたのFacebookページにページタブを追加するには、ページの上部にある前の写真でオレンジ色にハイライト表示されているFacebookアプリIDが必要です。 次に、次のURLにアクセスする必要がありますあなたのFacebookアプリのIDと以前に入力したストアのURLに置き換えることを確認して、ブラウザに

[https://www.facebook.com/dialog/pagetab?app\_id=&redirect\_uri=](https://www.facebook.com/dialog/pagetab?app_id={{YOUR_APP_ID}}&redirect_uri={{YOUR_STORE_URL}})

正しく行うと、Facebook上に「ページタブを追加」と書かれたページが表示され、Facebookページの中から1つを選択することができるようになります。 正しく行うと、Facebook上に「ページタブを追加」と書かれたページが表示され、Facebookページの中から1つを選択することができるようになります。

