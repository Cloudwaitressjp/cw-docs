---
description: ネットワークプリンタで印刷するためのガイドの方法
---

# 印刷 - Windows ネットワーク印刷

**ネットワーク印刷**

1. Windowsのコントロールパネルに移動してください。

![](../.gitbook/assets/untitled%20%281%29.png)

1. オープンデバイスとプリンタ

![](../.gitbook/assets/untitled-1.png)

1. 右クリックして「プリンタのプロパティ」を選択します。

![](../.gitbook/assets/untitled-2%20%285%29.png)

1. プリンタが表示されない場合は、以下の手順を使用して設定してください。 プリンタが動作しているかどうかをテストするには、「テストページを印刷する」を押してください。

![](../.gitbook/assets/untitled-3%20%281%29.png)

1. テストページが印刷されない場合 プリンタを正しく接続・設置してください。プリンタのセットアップを参照してください。 Windows用プログラムアプリケーションPushPrinterを開きます。 settings' cogに移動し、ドロップダウンリストからデフォルトまたはCloudWaitressプロバイダプロファイルを選択します。

![](../.gitbook/assets/untitled-4%20%282%29.png)

1. Automatically start PushPrinter」を有効にします。\(これにより、マシンのリセット時にアプリケーションが自動的に起動するようになります\)。

![](../.gitbook/assets/automatically-start-pushprinter.png)

1. プリンタボタンを押す

![](../.gitbook/assets/untitled-6.png)

1. プリンターの作成ボタンを使用して、プリンターを作成します。

![](../.gitbook/assets/untitled-7%20%284%29.png)

1. 作成したばかりのプリンタからAPIキーを含む設定を追加します。

{% hint style="info" %}
ネットワークプリンタの場合。 プリンタの名前を指定します。 APIプリンタを追加します（ストアのプリンタ設定にあります）。 セット部数 プリンタのIPアドレスを追加し、ポートを9100に設定します。\)
{% endhint %}

![](../.gitbook/assets/untitled-8%20%283%29.png)

{% hint style="danger" %}
注: 

プリンタ名 - プリンタ名は、CloudWaitress内で表示される名前です。

 プリンタ名 - CloudWaitress内でプリンタが表示する名前です。 

API Key - CloudWaitress内のプリンタ設定からコピーする必要があります。 

コピー数 - これは、印刷されるコピー数を決定します。

 印刷タイプ - これを機能させるには、Windows共有プリンタ（ESCPOS）に設定する必要があります。 Windows 共有プリンタ名 - これは、以前に追加された共有プリンタ名と完全に一致している必要があります。

スペースや特殊文字は避ける必要があります。
{% endhint %}

1. テストプリント 
2. プリンターの作成 お店に行って、
3. テスト注文をしてください。

\*\*\*\*

