[Amazon.co.jpの「未発送の注文」を表示(amzShowOpenOrders)](https://github.com/furyutei/amzShowOpenOrders)
===

- License: The MIT license  
- Copyright (c) 2021 風柳(furyu)  
- 対象ブラウザ： Google Chrome（[Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)が必要）、Firefox（[Tampermonkey](https://addons.mozilla.org/ja/firefox/addon/tampermonkey/)が必要）

[Amazon.co.jpの注文履歴](https://www.amazon.co.jp/gp/your-account/order-history)上でいつの間にか表示されなくなってしまった「未発送の注文」タブ（リンク）を表示するだけのユーザースクリプトです。  


■ インストール方法
---
[Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=ja)を入れたGoogle Chrome、もしくは、[Tampermonkey](https://addons.mozilla.org/ja/firefox/addon/tampermonkey/)を入れたFirefoxにて、  

> [amzShowOpenOrders.user.js](https://github.com/furyutei/amzShowOpenOrders/raw/master/src/js/amzShowOpenOrders.user.js)

をクリックし、指示に従ってインストール。  

■ 使い方
---
[注文履歴](https://www.amazon.co.jp/gp/your-account/order-history)画面を表示すると、「未発送の注文」というタブ（リンク）が追加されます。  
これをクリックすることで、未発送の注文一覧を表示できます（単に[orderFilter=openというクエリをつけたURL](https://www.amazon.co.jp/gp/your-account/order-history/?ie=UTF8&orderFilter=open)を開いているだけです）。  
