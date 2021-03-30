---
description: APIキーを設定する方法。これは、オンライン印刷設定をPushPrinterアプリケーションおよびレシートプリンターに接続するために使用されます。
---

# 印刷 - APIキー

1. 1.CloudWaitressアカウントにログイン[admin.cloudwaitress.com](https://admin.cloudwaitress.com/login?redirect=%2F)と設定\]に移動\]&gt; \[システム\]&gt; \[レシート印刷&gt;プリンタを作成します。 

![](../.gitbook/assets/1-create-printer.png)

2.プリンタに名前を付けます。PushPrinterの設定と同じ名前を使用することを推奨します。また、「自動印刷注文」と「自動印刷予約」をオンにすることをお勧めします。

![](../.gitbook/assets/untitled%20%282%29.png)

3.次に、\[プリンタ設定\]を選択し、次のことを確認します。

* 「印刷方法」-ESCPOSに設定されています
* 「ESCPOS印刷タイプ」-「ESCPOS画像」に設定されます。

{% hint style="warning" %}
**注**-お使いのプリンタがイメージプリンタの機能がない場合（正しく印刷されない、または印刷が非常に遅い）、これを「ESCPOSテキストのみ」に変更してください。
{% endhint %}

![](../.gitbook/assets/untitled-1%20%282%29.png)

4.画面の一番下までスクロールして、\[保存\]ボタンを押します。

5.次に、APIキーを表示し、右クリックしてクリップボードにコピーします。

![](../.gitbook/assets/untitled-2%20%283%29.png)

6.APIキーをPushPrinterの関連するAPIフィールドに貼り付けます。

