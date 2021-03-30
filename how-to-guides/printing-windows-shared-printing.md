---
description: USBプリンターの接続方法
---

# 印刷設定 - Windows （共有印刷）

1.Windowsのコントロールパネルに移動してください

![](../.gitbook/assets/untitled%20%283%29.png)

2.「デバイスとプリンター」を開きます  


![](../.gitbook/assets/untitled-1%20%283%29.png)

3.右クリックして、\[プリンタのプロパティ\]を選択します

![](../.gitbook/assets/untitled-2.png)

4.プリンタが表示されない場合は、次の手順を使用して設定してください。[プリンタの設定](https://www.notion.so/cloudwaitresswiki/Printing-Add-a-printer-18689e4654fe4978b20aeb82b581d81e)。

5.プリンタが機能していることをテストするには、\[テストページの印刷\]を押してください  


![](../.gitbook/assets/untitled-3%20%283%29.png)

6.テストページが印刷されない場合。次に、プリンタを正しく接続してインストールしてください。参照：[プリンタの設定](https://www.notion.so/cloudwaitresswiki/Printing-Add-a-printer-18689e4654fe4978b20aeb82b581d81e)。  


7.テストページが印刷される場合は、以下の設定でプリンターを共有してください。

![](../.gitbook/assets/untitled-4%20%281%29.png)

8. \[適用\]をクリックします

9.[**PushPrinter**](https://pushprinter.com/#windows)アプリケーションを開きます。設定が次のように表示されることを確認してください。

![](../.gitbook/assets/untitled-5.png)

10.次に、既存のプリンタを「プリンタの作成」または「編集」します。  


![](../.gitbook/assets/untitled-6%20%284%29.png)

11.次のような設定を追加します。作成したプリンターのAPIキー。プリンターの種類がWindows共有プリンター（ESCPOS）であることを確認します。Windows共有プリンター名は、以前に追加された共有プリンター名と一致する必要があります。

![](../.gitbook/assets/untitled-7%20%281%29.png)

**注意：**

**プリンター名**-これは、プリンターがCloudWaitress内に表示する名前です。

**APIキー**-これは、CloudWaitress内のプリンター設定からコピーする必要があります。

**部数**-これにより、印刷部数が決まります。

**印刷タイプ**-これを機能させるには、これをWindows共有プリンター（ESCPOS）に設定する必要があります。

**Windows共有プリンター名**-これは、以前に追加された共有プリンター名と正確に一致する必要があります。スペースや特殊文字は避けてください。

**11.次に、\[テスト印刷の送信\]を押してから、\[プリンタの作成\]を押します**  


