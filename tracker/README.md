# ArcGIS Field Maps で取得したトラッキングデータの保存とSpatially Enabled DataFrameを試す
「ArcGIS Field Maps で取得したトラッキングデータの保存とSpatially Enabled DataFrameを試す」のブログで紹介した、[サンプル ノートブック](https://github.com/EsriJapan/arcgis-samples-python-api/blob/master/tracker/save-track-to-featurelayer.ipynb)です。

## 概要

ArcGIS Online 上のArcGIS Notebooks で作成した、次の操作を試すサンプル ノートブックを出力して、整形したものです。

- Field Maps で取得したトラック データへアクセス
- 特定の日時のデータをクエリして確認
- Spatially Enabled DataFrame を試す
- クエリしたデータをフィーチャ レイヤー（Feature Layer）として保存 

## 免責事項
* 本リポジトリに含まれるノートブック ファイルはサンプルとして提供しているものであり、動作に関する保証、および製品ライフサイクルに従った Esri 製品サポート サービスは提供しておりません。
* 本ツールに含まれるツールによって生じた損失及び損害等について、一切の責任を負いかねますのでご了承ください。
* 弊社で提供しているEsri 製品サポートサービスでは、本ツールに関しての Ｑ＆Ａ サポートの受付を行っておりませんので、予めご了承の上、ご利用ください。詳細は[
ESRIジャパン GitHub アカウントにおけるオープンソースへの貢献について](https://github.com/EsriJapan/contributing)をご参照ください。

## ライセンス
Copyright 2022 Esri Japan Corporation.

Apache License Version 2.0（「本ライセンス」）に基づいてライセンスされます。あなたがこのファイルを使用するためには、本ライセンスに従わなければなりません。
本ライセンスのコピーは下記の場所から入手できます。

> http://www.apache.org/licenses/LICENSE-2.0

適用される法律または書面での同意によって命じられない限り、本ライセンスに基づいて頒布されるソフトウェアは、明示黙示を問わず、いかなる保証も条件もなしに「現状のまま」頒布されます。本ライセンスでの権利と制限を規定した文言については、本ライセンスを参照してください。

ライセンスのコピーは本リポジトリの[ライセンス ファイル](./LICENSE)で利用可能です。
