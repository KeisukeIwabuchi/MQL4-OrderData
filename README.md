# MQL4-OrderData
ポジションの構造体


| Name        | Description      |
|:------------|:-----------------|
| ticket      | チケット番号      |
| symbol      | 銘柄             |
| type        | 取引種別         |
| lots        | 取引数量         |
| open_time   | エントリー時刻    |
| open_price  | エントリー価格    |
| stoploss    | 逆指値価格       |
| takeprofit  | 指値価格         |
| close_time  | 決済時刻         |
| close_price | 決済価格         |
| expiration  | 有効期限         |
| commission  | 手数料           |
| swap        | スワップ損益     |
| profit      | 損益            |
| comment     | コメント        |
| magic       | マジックナンバー |


## Install
1. OrderData.mqhをダウンロード
2. データフォルダを開き、/MQL4/Includes/mql4_modules/OrderData/OrderData.mqhとして保存


## Usage
OrderData.mqhをincludeで読み込んで下さい。  
構造体OrderDataが使用可能になります。  
