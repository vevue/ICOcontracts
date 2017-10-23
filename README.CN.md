# ICO 计划

**<font color=green>合约地址</font>：<br>9d3d4cc1986d81f9109f2b091b7732e7d9bcf63b**

**<font color=green>接口ABI</font>：<br>https://github.com/vevue/ICOcontracts/blob/master/interface-abi.txt**

Vevue于2017年10月基于Qtum量子链网络发布用于众筹的合约。
总发行代币1亿枚，其中6000万代币用于众筹。
由于我们在预发行阶段完成了2000万代币的发放，本次众筹总额<font color=green> 4000万 </font>代币。
>Vevue代币分发方案 https://www.vevue.com/coins-distribution/

##### 兑换比例：
1 Qtum = 100 Vevue Token

##### 众筹时间：
起始于：区块高度 **35000**
结束于：区块高度 **90000**
>约2.2分钟产生1个区块

# 代币购买说明
### 1. 准备Qtum钱包
>本下载仅针对Windows及OSX用户
>Linux及其他官方发行版详见 https://github.com/qtumproject/qtum/releases

##### Windows
<li><a href="https://github.com/qtumproject/qtum/releases/download/mainnet-ignition-v1.0.2/qtum-0.14.3-win64.zip">qtum-0.14.3-win64.zip</a>

<li><a href="https://github.com/qtumproject/qtum/releases/download/mainnet-ignition-v1.0.2/qtum-0.14.3-win32.zip">qtum-0.14.3-win32.zip</a>

>解压后进入bin目录，其中qtum-qt即为钱包。
![](media/12.jpg)

##### OSX
<li><a href="https://github.com/qtumproject/qtum/releases/download/mainnet-ignition-v1.0.2/qtum-0.14.3-osx-unsigned.dmg">qtum-0.14.3-osx-unsigned.dmg</a>

### 2. 启动钱包并等待区块数据同步完成
![](media/13.jpg)

### 3. ICO合约地址验证
在左侧边栏依次选择：Smart Contract -> Call
合约地址填写：

```
9d3d4cc1986d81f9109f2b091b7732e7d9bcf63b
```

Interface(ABI)填写：

```
[{"constant":true,"inputs":[],"name":"name","outputs":[{"name":"","type":"string"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":false,"inputs":[{"name":"_spender","type":"address"},{"name":"_value","type":"uint256"}],"name":"approve","outputs":[{"name":"","type":"bool"}],"payable":false,"type":"function","stateMutability":"nonpayable"},{"constant":true,"inputs":[],"name":"_fundingStartBlock","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[],"name":"totalSupply","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":false,"inputs":[{"name":"_from","type":"address"},{"name":"_to","type":"address"},{"name":"_value","type":"uint256"}],"name":"transferFrom","outputs":[{"name":"","type":"bool"}],"payable":false,"type":"function","stateMutability":"nonpayable"},{"constant":true,"inputs":[],"name":"decimals","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[],"name":"_initialExchangeRate","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":false,"inputs":[],"name":"halt","outputs":[],"payable":false,"type":"function","stateMutability":"nonpayable"},{"constant":true,"inputs":[],"name":"initialExchangeRate","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[{"name":"_owner","type":"address"}],"name":"balanceOf","outputs":[{"name":"balance","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[],"name":"nativeDecimals","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":false,"inputs":[{"name":"_amount","type":"uint256"}],"name":"mintReservedTokens","outputs":[],"payable":false,"type":"function","stateMutability":"nonpayable"},{"constant":true,"inputs":[],"name":"saleAmount","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[],"name":"_fundingEndBlock","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[],"name":"owner","outputs":[{"name":"","type":"address"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[],"name":"fundingEndBlock","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[],"name":"symbol","outputs":[{"name":"","type":"string"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[{"name":"_Amount","type":"uint256"},{"name":"_exchangeRate","type":"uint256"},{"name":"_nativeDecimals","type":"uint256"},{"name":"_decimals","type":"uint256"}],"name":"getTokenExchangeAmount","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":false,"inputs":[{"name":"_to","type":"address"},{"name":"_value","type":"uint256"}],"name":"transfer","outputs":[{"name":"","type":"bool"}],"payable":false,"type":"function","stateMutability":"nonpayable"},{"constant":true,"inputs":[],"name":"halted","outputs":[{"name":"","type":"bool"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":false,"inputs":[],"name":"unhalt","outputs":[],"payable":false,"type":"function","stateMutability":"nonpayable"},{"constant":true,"inputs":[],"name":"fundingStartBlock","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":true,"inputs":[{"name":"_owner","type":"address"},{"name":"_spender","type":"address"}],"name":"allowance","outputs":[{"name":"remaining","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"constant":false,"inputs":[{"name":"_beneficiary","type":"address"}],"name":"buyTokens","outputs":[],"payable":true,"type":"function","stateMutability":"payable"},{"constant":false,"inputs":[{"name":"newOwner","type":"address"}],"name":"transferOwnership","outputs":[],"payable":false,"type":"function","stateMutability":"nonpayable"},{"constant":true,"inputs":[],"name":"tokenTotalSupply","outputs":[{"name":"","type":"uint256"}],"payable":false,"type":"function","stateMutability":"view"},{"inputs":[],"payable":false,"type":"constructor","stateMutability":"nonpayable"},{"payable":true,"type":"fallback","stateMutability":"payable"},{"anonymous":false,"inputs":[{"indexed":false,"name":"supply","type":"uint256"},{"indexed":true,"name":"to","type":"address"},{"indexed":false,"name":"amount","type":"uint256"}],"name":"Mint","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"name":"purchaser","type":"address"},{"indexed":true,"name":"beneficiary","type":"address"},{"indexed":false,"name":"value","type":"uint256"},{"indexed":false,"name":"amount","type":"uint256"}],"name":"TokenPurchase","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"name":"_owner","type":"address"},{"indexed":true,"name":"_spender","type":"address"},{"indexed":false,"name":"_value","type":"uint256"}],"name":"Approval","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"name":"_from","type":"address"},{"indexed":true,"name":"_to","type":"address"},{"indexed":false,"name":"_value","type":"uint256"}],"name":"Transfer","type":"event"}]

```
填写完成即可看到Function中出现的函数列表，下拉并选择<font color=green>name(06fdde03)</font>，之后点击最下面的<font color=green>调用智能合约</font>按钮。

![](media/1.jpg)

在进入的新页面看到Result结果中返回的值为**Vevue Token**即为操作正确。
如果显示为空说明调用的填写有问题，请重复并检查以上步骤或联系我们。

![](media/2.jpg)


### 4. 获取你的钱包地址

在左侧边栏选择Receive，之后点击页面中的**请求付款**，即可得到你的钱包地址，复制它。
>地址格式样例：QWYMhtPhwDbV3L8cjrBvLHkjkf9mNnEfcU

![](media/3.jpg)

点击菜单栏的**Help**并选择**Debug windows**。

![](media/4.jpg)

选择**控制台**并在下方输入以下代码：

```
gethexaddress 刚刚得到的钱包地址
```
>输入格式样例：
>
>```
>gethexaddress QWYMhtPhwDbV3L8cjrBvLHkjkf9mNnEfcU
>```

![](media/5.jpg)

输入回车即可得到你的16进制钱包地址（一会购买代币时用得上）
>16进制钱包地址格式样例：6d019f28780a3eeca51a150c6b461aa1c01b4ae5

![](media/6.jpg)

### 5. 购买代币

1. 在左侧边栏依次选择：Smart Contract -> SendTo。
2. 填写和步骤3中一样的**合约地址**和**Interface(ABI)**。
3. 之后在Function中选择**<font color=green>buyTokens(ec8ac4d8)</font>**。
4. 在**address _···**中填写步骤4中得到的**16进制钱包地址**。<br>
***（如：6d019f28780a3eeca51a150c6b461aa1c01b4ae5）***
5. 在**可选项**中的**数量**中填写要支出的Qtum代币数量。<br>
***（如：50）***

#####请**再次检查**所填数据，之后点击<font color=green>**Send To Contract**</font>发送代币。

![](media/7.jpg)

交易细节为

![](media/8.jpg)

### 6. 查看代币购买情况

点击左侧边栏**Transactions**即可看到刚刚的提交请求的状态为**等待确认**的问号。

![](media/9.jpg)

等待2～10分钟不等，待请求状态变成**确认中**说明代币发送成功。

![10](media/10.jpg)

因为本文编辑时当前区块高度尚未达到交易启动高度（35000）故提交的代币被合约退回。

##### 查看充值情况
1. 点击左侧边栏的**Smart Contract**，选择**Call**，合约地址和Interface(ABI)和步骤3中填写一致。
2. Function选择<font color=green>balanceOf(70a08231)</font>
3. address_ ···中填写步骤4中得到的**16进制钱包地址**
<br>（***如：6d019f28780a3eeca51a150c6b461aa1c01b4ae5***）

##### 在Result返回结果中即可看到你的余额。

![](media/11.jpg)








