# Verify peer count
`curl -X POST --data '{"jsonrpc":"2.0","method":"net_peerCount","params":[],"id":1}' localhost:8545`


~/Projects/anyrare/besu/bin/besu operator generate-blockchain-config --config-file=config.json --to=networkFiles --private-key-file-name=key


curl 'http://localhost:8545' \
  -H 'authority: testnet.anyrare.network' \
  -H 'sec-ch-ua: " Not A;Brand";v="99", "Chromium";v="96", "Google Chrome";v="96"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'user-agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/96.0.4664.93 Safari/537.36' \
  -H 'sec-ch-ua-platform: "Linux"' \
  -H 'content-type: application/json' \
  -H 'accept: */*' \
  -H 'origin: chrome-extension://nkbihfbeogaeaoehlefnkodbefgpgknn' \
  -H 'sec-fetch-site: none' \
  -H 'sec-fetch-mode: cors' \
  -H 'sec-fetch-dest: empty' \
  -H 'accept-language: en-US,en;q=0.9' \
  --data-raw '{"id":"1642612807572","jsonrpc":"2.0","method":"eth_chainId","params":[]}' \
  --compressed
