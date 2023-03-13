FROM ubuntu

WORKDIR geth 

COPY /testdata/genesis.json .
COPY geth  .
COPY party /party
RUN chmod +x ./geth

RUN ./geth init --datadir ./party genesis.json 

ENTRYPOINT ["./geth", "--networkid=1773", "--bootnodes=enode://3cab8f0b745baee7b221d9d5ff9c64ebc34b7407ce174541b3da186fdad0946823b4a6be45ecc54c33f5f0528c7451428e976702dc39b9395e2512a5feee751d@172.104.194.36:30303"]