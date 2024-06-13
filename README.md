先call這個取得驗證碼: (get)
https://wormhole.jumpcross.app/api/v1/challenge

再call這個:(post)
https://wormhole.jumpcross.app/api/v1/auth

然後連線WS:
wss://wormhole.jumpcross.app/api/v1/ws/login

然後要呼叫合約 我沒有寫範例:
sepolia
0x65589D2C60E588e16802552e964aFF4f31a01a45
mint(to address, username string)

然後await tx 確認交易的狀態是confirm

再來呼叫:(post)
https://stargate.jumpcross.app/api/v1/regist

綁定推特:
https://stargate.jumpcross.app/api/v1/auth/x

綁定dc:
https://stargate.jumpcross.app/api/v1/bind/discord

檢查用戶資訊:
https://stargate.jumpcross.app/api/v1/check
