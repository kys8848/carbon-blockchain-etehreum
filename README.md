# carbon-blockchain-etehreum
Using private ethereum and web(web3,html) / smart contract based carbon credit trading system


[cmd창]
geth --networkid 4649 --nodiscover --maxpeers 0 --datadir C:\data_testnet --mine --minerthreads 1 --rpc --rpcaddr "127.0.0.1" --rpcport 8545 --rpccorsdomain "*" --rpcapi "admin,db,eth,debug,miner,net,shh,txpool,personal,web3" --unlock 0 --password C:\data_testnet\passwd --verbosity 6 

2>> /root/data_testnet/geth.log  <--로그저장이 필요할때



[cmd창]
geth attach rpc:http://localhost:8545
eth.blockNumber
eth.mining

[eth. 계정조회/추가/삭제]


[브라우저] --> nana.sol 은 작동안함!!!  // 12장_2.5 Contract에서 정상작동 
file:///C:/Users/LG/Downloads/browser-solidity-gh-pages/browser-solidity-gh-pages/index.html#optimize=false&version=soljson-v0.4.23+commit.124ca40d.js

//web3 provider환경에서 작동시켜야함//
counterMaster에서 create 후 -> abi주소값을 --> 웹 masterAbi 주소에 입력

file:///C:/data_testnet/12%EC%9E%A5_%EB%A6%AC%EC%8A%A4%ED%8A%B823_index%20-%20%EB%B3%B5%EC%82%AC%EB%B3%B8.html

file:///C:/data_testnet/12%EC%9E%A5_%EB%A6%AC%EC%8A%A4%ED%8A%B826_monitor.html

ABI주소는 어디서 ? 

// 연결할 Contract(CounterMaster) 주소 
주소 : 0xa4520534d48a7fef94c43945b077e8abbcfe8482
새로생성한주소 : 0xbbf289d846208c16edc8474705c748aff07732db

<웹어플리케이션쪽 계정입력>
사용자명:&nbsp;<input type="text" id="userName" value="0x835b3e4bd3b392d9475f1bceeb06523037108c23">&nbsp;
패스워드:&nbsp;<input type="text" id="password" value="testuser2">&nbsp; <input type="button" value="login" onclick="login();" />



참고
> eth.accounts
0x16cc03e13edc4309ccede2ee20e8b8096fc37a34 // accounts[0] =pass0
0xbe4a5f2e914aba16eb91928005a9c4279f682819 // accounts[1] = ??
0xe4d35b57a16e1612b1af608ef1f3bed2862ff7c // accounts[2] = ??
0xc58215d0903871af100cb5608d1a9a6b67611ad6  // accounts[3] = admin



