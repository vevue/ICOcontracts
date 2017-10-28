# ICO PLAN

**<font color=green>Smart Contract Address</font>：<br>9d3d4cc1986d81f9109f2b091b7732e7d9bcf63b**

**<font color=green>Interface ABI</font>：<br>https://github.com/vevue/ICOcontracts/blob/master/interface-abi.txt**

Vevue create smart contract through Qtum main network on October 2017.
We released 100 millions totally and 40 millions of all for ICO.

>VEVUE TOKEN DISTRIBUTION https://www.vevue.com/coins-distribution/

##### Exchange Rate：
1 Qtum = 100 Vevue Token

##### ICO Duration：
Start Block: **35000**
End Block **90000**
>About 2.2 minutes birth 1 Block

# Buy Token
### 1. Prepare Qtum Wallet
>Linux and more release https://github.com/qtumproject/qtum/releases

##### Windows
<li><a href="https://github.com/qtumproject/qtum/releases/download/mainnet-ignition-v1.0.2/qtum-0.14.3-win64.zip">qtum-0.14.3-win64.zip</a>

<li><a href="https://github.com/qtumproject/qtum/releases/download/mainnet-ignition-v1.0.2/qtum-0.14.3-win32.zip">qtum-0.14.3-win32.zip</a>

> Unzip and enter "bin" folder, launch qtum-qt to run the wallet。
![](media/12.jpg)

##### OSX
<li><a href="https://github.com/qtumproject/qtum/releases/download/mainnet-ignition-v1.0.2/qtum-0.14.3-osx-unsigned.dmg">qtum-0.14.3-osx-unsigned.dmg</a>

### 2. Launch Wallet and start Blockchain Synchronization
![](media/13.jpg)

### 3. Check ICO Smart Contract
Select **Smart Contract -> Call** on the left side
Input in Contract Address：

```
9d3d4cc1986d81f9109f2b091b7732e7d9bcf63b
```

Input in Interface(ABI)：

```
[{"constant":true,"inputs":[],"name":"name","outputs":[{"name":"","type":"string"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":false,"inputs":[{"name":"_spender","type":"address"},{"name":"_value","type":"uint256"}],"name":"approve","outputs":[{"name":"","type":"bool"}],"payable":false,"type":"function","stateMutability":"nonpayable"},{"constant":true,"inputs":[],"name":"_fundingStartBlock","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[],"name":"totalSupply","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":false,"inputs":[{"name":"_from","type":"address"},{"name":"_to","type":"address"},{"name":"_value","type":"uint256"}],"name":"transferFrom","outputs":[{"name":"","type":"bool"}],"payable":false,"type":"function","stateMutability":"nonpayable"},{"constant":true,"inputs":[],"name":"decimals","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[],"name":"_initialExchangeRate","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":false,"inputs":[],"name":"halt","outputs":[],"payable":false,"type":"function","stateMutability":"nonpayable"},{"constant":true,"inputs":[],"name":"initialExchangeRate","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[{"name":"_owner","type":"address"}],"name":"balanceOf","outputs":[{"name":"balance","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[],"name":"nativeDecimals","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":false,"inputs":[{"name":"_amount","type":"uint256"}],"name":"mintReservedTokens","outputs":[],"payable":false,"type":"function","stateMutability":"nonpayable"},{"constant":true,"inputs":[],"name":"saleAmount","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[],"name":"_fundingEndBlock","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[],"name":"owner","outputs":[{"name":"","type":"address"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[],"name":"fundingEndBlock","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[],"name":"symbol","outputs":[{"name":"","type":"string"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[{"name":"_Amount","type":"uint256"},{"name":"_exchangeRate","type":"uint256"},{"name":"_nativeDecimals","type":"uint256"},{"name":"_decimals","type":"uint256"}],"name":"getTokenExchangeAmount","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":false,"inputs":[{"name":"_to","type":"address"},{"name":"_value","type":"uint256"}],"name":"transfer","outputs":[{"name":"","type":"bool"}],"payable":false,"type":"function","stateMutability":"nonpayable"},{"constant":true,"inputs":[],"name":"halted","outputs":[{"name":"","type":"bool"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":false,"inputs":[],"name":"unhalt","outputs":[],"payable":false,"type":"function","stateMutability":"nonpayable"},{"constant":true,"inputs":[],"name":"fundingStartBlock","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[{"name":"_owner","type":"address"},{"name":"_spender","type":"address"}],"name":"allowance","outputs":[{"name":"remaining","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":false,"inputs":[{"name":"_beneficiary","type":"address"}],"name":"buyTokens","outputs":[],"payable":true,"type":"function","stateMutability":"payable"},{"constant":false,"inputs":[{"name":"newOwner","type":"address"}],"name":"transferOwnership","outputs":[],"payable":false,"type":"function","stateMutability":"nonpayable"},{"constant":true,"inputs":[],"name":"tokenTotalSupply","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"inputs":[],"payable":false,"type":"constructor","stateMutability":"nonpayable"},{"payable":true,"type":"fallback","stateMutability":"payable"},{"anonymous":false,"inputs":[{"indexed":false,"name":"supply","type":"uint256"},{"indexed":true,"name":"to","type":"address"},{"indexed":false,"name":"amount","type":"uint256"}],"name":"Mint","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"name":"purchaser","type":"address"},{"indexed":true,"name":"beneficiary","type":"address"},{"indexed":false,"name":"value","type":"uint256"},{"indexed":false,"name":"amount","type":"uint256"}],"name":"TokenPurchase","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"name":"_owner","type":"address"},{"indexed":true,"name":"_spender","type":"address"},{"indexed":false,"name":"_value","type":"uint256"}],"name":"Approval","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"name":"_from","type":"address"},{"indexed":true,"name":"_to","type":"address"},{"indexed":false,"name":"_value","type":"uint256"}],"name":"Transfer","type":"event"}]

```
You could see the functions list in Function part, choose <font color=green>name(06fdde03)</font>，and click <font color=green>Call Contract</font> button。

![](media/1.jpg)

If you see the world **Vevue Token** display in the Result part, Congratulations! You success!
If it says nothing，please check step and repeat or Contact us。

![](media/2.jpg)


### 4. Get your Wallet Address

Select **Receive** on the left side，and click the **Request payment** and then you could get your wallet address, copy it。
>e.g. QWYMhtPhwDbV3L8cjrBvLHkjkf9mNnEfcU

![](media/3.jpg)

Click **Help** on Menu and click **Debug windows** next。

![](media/4.jpg)

Select **Console** and run the code under it：

```
gethexaddress the address you just get
```
>e.g.
>
>```
>gethexaddress QWYMhtPhwDbV3L8cjrBvLHkjkf9mNnEfcU
>```

![](media/5.jpg)

Press Enter and then you could get your Hex Wallet Address
>Hex Wallet Address e.g. 6d019f28780a3eeca51a150c6b461aa1c01b4ae5

![](media/6.jpg)

### 5. Buy Token

1. Select **Smart Contract -> SendTo** on the left side.
2. Input the **Contract Address** and **Interface(ABI)** just the same as Step 3。
3. Select **<font color=green>buyTokens(ec8ac4d8)</font>** in Function。
4. Input the Hex Wallet Address from Step 4 in **address _···**
***(e.g. 6d019f28780a3eeca51a150c6b461aa1c01b4ae5)***
5. Input the number you want to buy through Qtum in **Optional** **Amount**<br>
***(e.g. 50)***

##### Please Double Check about your input，and then click <font color=green>**Send To Contract**</font> for sending。

![](media/7.jpg)

Details

![](media/8.jpg)

### 6. Check Token Status

Choose **Transactions** on the left side and then you could see the unconfirm's item.

![](media/9.jpg)

Waiting 2～10 minutes still the status turns to **Confirmed**means sending success.

![10](media/10.jpg)

##### Check Recharge Status
1. Choose **Smart Contract** on the left side and choose **Call**, Input in Contract Address and Interface(ABI) just the same as Step 3.
2. Choose <font color=green>balanceOf(70a08231)</font> in Functions
3. Input the Hex Wallet Address in **address_ ···**
<br>(***e.g.6d019f28780a3eeca51a150c6b461aa1c01b4ae5***

##### You could see the Vevue Token in Result。

![](media/11.jpg)








