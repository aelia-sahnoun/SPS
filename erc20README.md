# SPS
ERC20 contract creation
url -X 'POST' \
  'https://api.vorj.app/main/v1/erc20' \
  -H 'accept: application/json' \
  -H 'x-api-key: 6053186309eff12ab7d1aba271d012b6304171b99cfe36fa4adf70f37369d2ed' \
  -H 'Content-Type: application/json' \
  -d '{
  "name": "food advantages",
  "symbol": "foad",
  "decimals": 0,
  "totalSupply": "10000000000",
  "contractFunctionality": {
    "burn": false,
    "pause": true
  }
}'
