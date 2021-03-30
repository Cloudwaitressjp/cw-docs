---
description: >-
  オンラインで注文を受け入れるには、オンラインメニューを設定する必要があります。レストラン管理画面の[メニュー]セクションで、すべてのメニューを作成および管理ができます。
---

# メニューを設定する

{% embed url="https://youtu.be/Nyyr2vwB1Io" caption="Menu setup video tutorial" %}

セットアッププロセス

メニューはツリー構造で構成されています。メニューにはカテゴリが含まれ、カテゴリには料理が含まれます。一般的なセットアッププロセスは次のとおりです。

1. メニューを作成する
2. メニューの中にすべてのカテゴリを作成します
3. カテゴリの中に料理を作成する
4. 料理にカスタマイズを追加するためのオプションセットを作成する
5. 特定の料理の属性を強調するために料理タグを作成します

{% hint style="info" %}
あなたが必要とするメニューは1つだけでしょう。特定のアイテムが特定の方法で制限されている場合は、複数のメニューが便利です。あなたの要件に応じて、「朝食」メニューまたは「デリバリー」メニューを作成する必要があるかもしれません。
{% endhint %}

メニュー構成例

```text
- メニューです。メインメニュー
-- カテゴリーは？ピザ
---- ディッシュ。ハム＆チーズ
---- ディッシュ。マルグリタ
---- ディッシュ。ベジースプリーム
-- カテゴリーは以下の通りです。サイド
---- 料理。手羽先
---- ディッシュ。フライドポテト
-- カテゴリ. 飲み物
---- ディッシュ。アイスティー
---- Dish. コーラ
---- ディッシュ。水
```

メニュー

これらは、実際のメニューを表しています。多くの店舗には、常に利用できるメインメニューが1つだけあります。時間帯で分けてランチ＆ディナーメニューまたはテイクアウトのみのメニューを持っている店舗もあります。オンラインストアを機能させるには、少なくとも1つのメニューが必要です。

メニューの可用性は、注文の種類（店内、テイクアウト、デリバリー）、注文のタイミング（たとえば、事前注文のみ）などの特定の条件によって異なります。また、特定の曜日と時間帯を制限することもできます。

{% hint style="info" %}
利用できるメニューが1つしかない場合は、メニューに制限を設ける必要はありません。システム店舗の提供状況に合わせて制限することができ、メニューはそれに応じて機能します。メニューを特定の条件に制限する必要があるのは、複数のメニューがある場合のみです。
{% endhint %}

カテゴリー

カテゴリはメニューの中の分類を表します。たとえば、メニューが1つある場合、カテゴリには次のものが含まれます。

* 前菜
* メイン 
* サイドメニュー
* ドリンク
* デザート

{% hint style="info" %}
場合によっては、カテゴリを使用する代わりに、別のメニューを作成する必要があります。たとえば、スピリッツ、ワイン、ビール、ソーダなど、さまざまなカテゴリの飲み物がある場合、フードメニューに追加するのではなく、新たにドリンクメニューを作成することをおすすめします。
{% endhint %}

料理

料理は実際に購入できるアイテムを表しています。単品とコンボの2種類があります。

スタンダードディッシュ

単品料理

次のようなアイテムを作成します。

* サンドイッチ
*  ピザ 
* バニラアイス

食材

単品料理には、材料のリストを表示することができます。お客様は料理を選ぶときに、必要な材料を取り除くことができます。

**コンボ料理**

コンボは、他の料理を合わせて頼むことができます。これにより、顧客がさまざまな単品料理を選択するための選択肢のリストを作成できます。たとえば、次のものを作成できます。

* ピザ3枚、サイド2枚、ドリンク2杯をお選びください
*  ハンバーガーを選び、サイドメニューとドリンクをお選びください

はじめに単品料理をいくつか作成する必要があります。次に、コンボを作成するときに、3つのピザの選択肢、1つのドリンクの選択肢を作成します

{% hint style="info" %}
コンボ料理には、オプションセットや材料を直接含めることはできません。代わりに、お客様がコンボ内で単品料理を選択したときに、選択した単品料理にオプションセットが割り当てられている場合、ユーザーはそれに応じてカスタマイズできます。
{% endhint %}

**料理の注文受付**

料理には3つのステータスがあります。それは以下の通りです。

* 非表示 - メニューから料理を非表示にします
* 利用不可 - 利用時間を制限し、利用できない場合はメッセージを表示します
*  在庫切れ - 注文を不可にし、在庫切れと表示

メニュー設定画面で、料理の左側にあるチェックボックスをオンにすることで、料理のステータスを編集できます。次に、ポップアップメニューから目的のステータスを選択します。

オプションセット

すべての料理のカスタマイズは、オプションセットを使用して行われます。オプションセットは、任意の数の料理に割り当てることができる構成可能なオプションのセットです。オプションセットを使用すると、次のような要件を作成できます。

* ピザ生地を選択してください 
* 1つまたは複数のソースを選択します
* 4種類以上のトッピングをお選びください。

{% hint style="info" %}
条件付きオプションセットのを作成する方法については、オプションセットの作成時に使用できる各設定の説明をお読みください。各設定について詳しく説明します。または、上記のメニュー設定ビデオを見て、上記の例を作成してください
{% endhint %}



タグを使用すると、カスタマイズ可能な視覚的インジケータを使用して、料理に関する特定の属性を指定できます。次のような属性のタグを作成できます。

* スパイシー
* ビーガン
* グルテンフリー

よくあるメニュー設定の問題

ストアの下にメニューやカテゴリが表示されない

メニューをオンラインストアに表示するには、少なくとも1つのカテゴリと1つの料理を追加してください。

メニューの画像を大きくする

すべての画像を最適化するには、Webサイト[https://www.birme.net](https://www.birme.net/)または[https://tinypng.com/](https://tinypng.com/)を使用することをお勧めします。表示できる最大画像幅が約600ピクセルしです。すべての画像がそれより大きくないことを確認してください。
