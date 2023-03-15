geth init --datadir ./party testdata/genesis.json 

./geth account new

0x3604db9Dc197dbbcc0dbE93c469c5b7fB0B6a7e3

nohup ./geth --networkid 1773  --port 30303 --http --http.port 8545 --http.addr 0.0.0.0 --http.api personal,eth,net,admin --http.corsdomain '*' --http.vhosts '*' --allow-insecure-unlock  --syncmode full --ws --ws.addr 0.0.0.0    --datadir ./party --nodiscover --mine --miner.etherbase 0x3604db9Dc197dbbcc0dbE93c469c5b7fB0B6a7e3 &

--bootnodes

172.104.194.36:30303

"enode://8904d18d98034bf36cc8aed2ff33fd5a59e92bcd549d5f865792ea2864170b5a88acdde54d799148071137b7ab2b9c544d82ad7354ac053fffb242e5124b3d1c@172.104.194.36:30303"

"enode://1918351925bd05be23486fe60fc4635f3a25abb424645f725848dd158985d61f608a8ba5042eb959cc59f71c5e5200e088220839fbacbdb794867f773c902aee@65.109.52.145:60606"