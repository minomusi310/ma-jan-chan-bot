# ma-jan-chan-bot

## line bot

### ほしい機能
- 日々の対局招集
- 順位表の表示

### Line Developersの登録
https://developers.line.biz/ からアカウントの登録。  
Lineアカウントを使用して登録もできる。

### チャネルの作成
[公式ガイド](https://developers.line.biz/ja/docs/messaging-api/getting-started/#%E3%83%81%E3%83%A3%E3%83%8D%E3%83%AB%E3%81%AE%E4%BD%9C%E6%88%90)

何のことかと思うが、Line debelopersにログインしたのちに  
プロバイダを新規登録  
→アイコンが必要だが、著作権など気になるのでいらすとやを使用。  

meessaging API として作成

さて、tokenの発行だが、  
[カスペルスキーブログ](https://blog.kaspersky.co.jp/tokens-on-github/22922/)にあるように  
こういった危険な奴は注意が必要。  
github以外のやり方での共有がよい。


## 言語はpython
https://github.com/line/line-bot-sdk-python

とりあえずsdk入れておく  
``` pip install line-bot-sdk ```

