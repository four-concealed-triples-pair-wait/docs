# AWSざっくり料金まとめ

## cloudfront

- インターネットへのリージョンデータ転送アウト(GB単位)  
0.114USD  
- オリジンへのリージョン内データ転送アウト(GB単位)  
0.060USD  
- HTTP メソッドのリクエスト料金 (1 万件あたり)  
0.0120USD  

### 無料枠（毎月）

1 か月あたり 1 TB のデータ転送 (OUT)  
1 か月あたり 10,000,000 件の HTTP または HTTPS リクエスト  
1 か月あたり 200 万件の CloudFront 関数呼び出し

## S3

- データ保存料金  
  0.025USD/GB
- リクエストとデータ取り出し（GET、SELECT、他のすべてのリクエスト (1,000 リクエストあたり)）  
  0.00037USD
- データ転送  
  Croudfrontへのデータ転送は無料

## APIgateway

- REST API (100 万あたり)  
  4.25USD  
- データ転送（GBデータあたりの単価）  
  0.09USD

## Lambda

- リクエスト（100 万件あたり）  
0.20USD  
- メモリ使用量（GB-秒あたり ）  
0.0000166667USD  
※128 MB から 10,240 MB までの任意の量のメモリを 1 MB 単位で関数に割り当てることができます。

### 無料枠（毎月）

100万リクエスト  
1 か月あたり 40 万 GB-s  

## DynamoDB

- キャパシティユニット  
  書き込み要求単位 書き込み要求ユニット 100 万あたり：1.25USD  
  読み出し要求単位 読み出し要求ユニット 100 万あたり：0.25USD  
- データストレージ(保存容量)  
0.25USD/GB
- データ転送  
※同じ AWS リージョン内の他の AWS のサービスとの間のデータ転送にも課金されません (0.00 USD/GB)

### 無料枠

25GB  
1 か月あたり 40 万 GB-s  
https://qiita.com/Takayuki_Nakano/items/b1b383391a930dac43c7

## Route53

- ホストゾーン（１個あたり/月）  
  0.50 USD  
- 100万クエリごと  
  0.500 USD  

## その他

- ドメイン購入