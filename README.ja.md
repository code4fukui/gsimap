# gsimap

地理院地図のWebマップソースコードです。

## デモ
- 公式のGSI Mapsサイト: http://maps.gsi.go.jp/
- このリポジトリに基づいた直接的なデモ: http://gsi-cyberjapan.github.io/gsimaps/

## 機能
- 地理院地図の機能をそのまま利用可能
- 独自のカスタマイズが可能

## 必要環境
特に必要ありません。

## 使い方
1. このリポジトリをダウンロードします。
2. ファイルをWebサーバーに配置します。 
3. index.htmlを開きます。
ロゴなどのカスタマイズを行いたい場合は、index.htmlを編集してください。
右下のアクセスカウンターは無効になっています。

ファイルシステムから[index.html](index.html)を開いても、ほとんどの機能が動作します。
ただし、ベクタータイルデータを扱う機能などは、Webサーバー上でindex.htmlを開いた場合にのみ動作します。

## データ・API
- このリポジトリは、地理院が運営するGSI Mapsのソースコードを提供しています。
- Leaflet、jQuery、その他ライブラリの[それぞれのライセンス](LICENSE_LIBRARIES.md)が適用されます。
- 地理院コンテンツライセンスに基づき、2条項BSDライセンス(Leafletと同じ)が適用されます。
- プルリクエストは2条項BSDライセンスに従い、マージ時にGSIへの帰属が追加されます。
- gsimapsは、東京大学CSISが運営する<a href='http://newspat.csis.u-tokyo.ac.jp/geocode/'>サービス</a>を利用しています。
- gsimapsから呼び出されるサーバーサイドサービスの継続的な運用は保証されません。
- gsimapsから呼び出されるサーバーサイドサービスは予告なく更新または廃止される可能性があります。
- この英語版の説明は暫定的なものであり、公式ではありません。

ライセンスファイル[LICENSE](LICENSE)も参照してください。

## 関連情報
- レイヤー定義編集ツール(このリポジトリから): http://gsi-cyberjapan.github.io/gsimaps/config.html
- レイヤー定義の仕様(同じくgithubリポジトリ): https://github.com/gsi-cyberjapan/layers-dot-txt-spec

## ハッシュタグ
このリポジトリのハッシュタグは #gsimaps です。
Twitter: https://twitter.com/hashtag/gsimaps