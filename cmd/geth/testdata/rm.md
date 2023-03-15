geth init --datadir ./party testdata/genesis.json 

./geth account new

0xee3f6e39CcFa13B776FE2D4b158dF3C3B1766181

nohup ./geth --networkid 1773  --port 30303 --http --http.port 8545 --http.addr 0.0.0.0 --http.api personal,eth,net --http.corsdomain '*' --http.vhosts '*' --allow-insecure-unlock  --syncmode full --ws --ws.addr 0.0.0.0    --datadir ./party --nodiscover --mine --miner.threads 1 --miner.etherbase 0xee3f6e39CcFa13B776FE2D4b158dF3C3B1766181 &

--bootnodes

172.104.194.36:30303

enode://8904d18d98034bf36cc8aed2ff33fd5a59e92bcd549d5f865792ea2864170b5a88acdde54d799148071137b7ab2b9c544d82ad7354ac053fffb242e5124b3d1c@172.104.194.36:30303?discport=0"