# Token assets for KAHF

### 1. 使用checksum格式的合约地址
Checksum地址是指在以太坊网络中包含大写和小写字母的合约地址。你可以通过在QitmeerEVM浏览器搜索代币的合约地址，搜索完成后，在左上角的地址即为checksum格式的合约地址。例如USDT的checksum格式的合约地址为：
0xf16FE840D83d23509fe5642FC1642BC302E12E0d。


### 2. 代币图标
```
文件扩展名：png，请勿大写PNG
文件名称：logo.png
大小：256px X 256px
图标背景：推荐使用透明背景‌
```

### 3. 代币信息文件
```
文件扩展名：json，请勿大写JSON
文件名称：info.json
```
内容： info.json文件中必须包含以下信息，请确保详细信息正确无误并遵循格式要求。合约地址应遵循checksum地址格式（请参考下面的示例）。
注意：如文件格式不正确将无法通过审核！
```
{
    "name": "Meer USD",
    "website": "https://www.qitmeer.io",
    "description": "",
    "explorer": "https://evm.meerscan.io/address/0xf16FE840D83d23509fe5642FC1642BC302E12E0d",
    "type": "ERC20",
    "symbol": "USDT",
    "decimals": 18,
    "status": "active",
    "id": "0xf16FE840D83d23509fe5642FC1642BC302E12E0d"
}
```
