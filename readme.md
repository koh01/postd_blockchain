以下のお勉強
http://postd.cc/learn-blockchains-by-building-one/


マイニング
http://localhost:5000/mine

トランザクションの作成（POST）
http://localhost:5000/transactions/new

curl -X POST -H "Content-Type: application/json" -d '{
"sender": "d4ee26eee15148ee92c6cd394edd974e",
"recipient": "someone-other-address",
"amount": 5
}' "http://localhost:5000/transactions/new"

チェーンのチェック
http://localhost:5000/chain
