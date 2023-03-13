geth init --datadir ./party testdata/genesis.json 


nohup ./geth --networkid 1773  --port 30303 --http --http.port 8545 --http.addr 172.104.194.36 --http.api personal,eth,net --http.corsdomain '*' --allow-insecure-unlock  --syncmode full  --datadir ./party --nodiscover --mine --miner.etherbase 0x9E405885F373c73CFf78134980249e1b7337D760 &


enode://3cab8f0b745baee7b221d9d5ff9c64ebc34b7407ce174541b3da186fdad0946823b4a6be45ecc54c33f5f0528c7451428e976702dc39b9395e2512a5feee751d@172.104.194.36:30303

"enode://3cab8f0b745baee7b221d9d5ff9c64ebc34b7407ce174541b3da186fdad0946823b4a6be45ecc54c33f5f0528c7451428e976702dc39b9395e2512a5feee751d@172.104.194.36:30303?discport=0"