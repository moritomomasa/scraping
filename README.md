※スクレイピングといえば beautifulsoup では？<br>
→beautifulsoup は HTML を抽出してデータを取り出すため、この方法では Google 検索結果のデータが取り出せない。(実際 Google の検索結果の方が数が多く種類も豊富なの で Google でスクレイピングしたい)<br>
→selenium では web ブラウザを起動させてからプロブラムを組むため Google 検索結果にも対応可能

# 手順 1.GoogleChrome のバージョン確認

[こちら](https://cs.myjcom.jp/knowledgeDetail?an=000004134)を参考に確認する

# 手順 2．WebDriver のインストール

[こちら](https://sites.google.com/chromium.org/driver/downloads)から手順 1 で確認した GoogleChrome のバージョンと合った Driver をダウンロードする

# 手順 3．selenium のインストール

```
pip install selenium
```
