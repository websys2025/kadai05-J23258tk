## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
エンドポイント：https://zipcloud.ibsnet.co.jp/api/search
機能：日本の郵便番号から住所情報（都道府県、市区町村、町域）を取得することができる無料のAPI。逆に住所から郵便番号を調べる機能はない。
* リクエストとレスポンスのフォーマット
  https://zipcloud.ibsnet.co.jp/api/search?zipcode=1000001

### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
API名：The Cat API
参照URL: https://thecatapi.com/
* エンドポイントと機能
エンドポイント:https://api.thecatapi.com/v1/images/search
機能:ランダムな猫の画像を1枚取得できるAPI。猫種を指定したり、画像の数を増やしたりすることもできる。
* リクエストとレスポンスのフォーマット
 https://api.thecatapi.com/v1/images/search
例
[
  {
    "id": "MTY3ODIyMQ",
    "url": "https://cdn2.thecatapi.com/images/MTY3ODIyMQ.jpg",
    "width": 500,
    "height": 333
  }
]

### Q3-3. 感想
* 今回の課題で苦労したこと
APIの仕様を理解するのに時間がかかった。特にリクエストパラメータの形式や、エラー時のレスポンスの扱いについて調査が必要だった。
* 演習を通して理解できたこと
APIは、あらかじめ決められた形式でリクエストを送ることで、必要なデータを効率よく取得できるという点がよく理解できた。また、JSON形式のレスポンスの扱い方も学ぶことができた。
* Web APIの利便性や課題など
Web APIを使えば、他のサービスの機能やデータを自分のアプリケーションに簡単に組み込めるとても便利なもの。一方で、APIの仕様変更や制限（回数制限や認証など）には注意が必要だと感じた。
