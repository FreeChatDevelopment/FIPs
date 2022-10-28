---
fip: 14
标题: FreechatDAO和Freechat的流动性空投激励方案
描述: 所有潜在投资人为Freechat Coin提供流动性的奖励。
状态: 草案
类型: 机制
作者: Jack long （jacklong@freechat.world）
创建时间: 2022-10-23
修改时间: 2022-10-28
---

## Freechat Github Fips: 

https://github.com/FreeChatDevelopment/FIPs/blob/main/FIP/fip-14.md

  | 提案时间 | 链接 | 结果 |
  |:-:|:-:|:-:|
  | YYYY-MM-DD |FreechatDAO社区对应的提案链接|待定|

# FreechatDAO和Freechat的激励方案

## 目的
补充Freechat Coin（FCC）流动池资金，发放Freechat Coin（FCC）空投进行去中心化治理。

## 激励方案
   为确保快速的积累流动池，激励方式公示如下：

   - **激励轮次**：第一轮
   - **激励金额**：10,000,000 USD
   - **邀请方式**：定向邀请
   - **激励用途**：全部投入流动性池
   - **操作方式**：参与激励的投资人以自有钱包的方式自行设置流动池及范围。
   - **目标交易对**：[USDT-FCC](https://info.uniswap.org/#/pools/0x03de8b89caa2bbe8bf09979d370aaf08a35cbfa1])
   - **窗口截止时间**：2023-12-31

 #### 流动性激励（LP激励）

   - **激励定价**：1 FCC = 0.1 USDT   

     新一轮投资人作为FreechatDAO及Freechat的LP，向以下交易对提供流动性：
   
     交易对：USDT-FCC

     流动池：https://info.uniswap.org/#/pools/0x03de8b89caa2bbe8bf09979d370aaf08a35cbfa1

     流动性提供币种：USDT

     流动性提供数量：不低于10,000 USDT，不超过7,000,000 USDT

     流动性提供时间：至少12个月（2023-12-31日解锁）

     激励回报：为投资人奖励提供流动性金额等额的 FCC 代币

     计算公式：提供流动池的USDT金额/0.1 USDT（FCC 定价）=获得数量
     
         示例：例如A投资人向流动池提供10,000 USDT，那么A投资人按照计算公式将会获得10,000/0.1=100,000 FCC
     
     锁仓限制：流动性奖励代币2025年8月22日解锁，解除限制后将根据[FIP-15](https://github.com/FreeChatDevelopment/FIPs/blob/main/FIP/fip-15.md)的名单进行发放。

     限制条款：如果提供的流动性不满足12个月，中途撤出流动性，将取消配送资格。快照检查6次。

     风险提示：投资人在提供流动性时，请谨慎设置交易对的价格范围，流动池会根据 FCC 的市场进行变化，比如购买、出售 FCC 等行为会影响到流动池的变化。当 FCC 价格在设置的流动性范围时，将会使用该流动池。


## 快照时间及检查
快照用于记录账户活动状况及变动状况，保证激励规则的公平性及透明度，保护投资者权益和社区权益。

快照时间：

- **第一次**：2022-12-31 23:00
- **第二次**：随机
- **第三次**：随机
- **第四次**：随机
- **第五次**：随机
- **第六次**：2023-12-31 23:00

根据规则，参与定向邀请的地址将会进行快照检查6次，期间不能有任何操作如撤销流动性、增加流动性，快照记录六次都应当一致，不一致将取消流动性奖励资格。

## 相关资料

社区治理：
https://snapshot.org/#/freechatdao.eth

社区协议条款：
https://docs.freechat.world

项目开源仓库：
https://github.com/FreeChatDevelopment

代币经济学与白皮书：
https://docs.freechat.world/fdao-she-qu

FreechatDAO社群：
https://twitter.com/freechat_app

商业计划书：https://github.com/FreeChatDevelopment/FIPs/blob/main/assets/fip-14/FreechatBP.pdf

Freechat Coin流动池与交易对：

[USDT-FCC](https://info.uniswap.org/#/pools/0x03de8b89caa2bbe8bf09979d370aaf08a35cbfa1)

[ETH-FCC](https://info.uniswap.org/#/pools/0xf9c97668f97160b18c87a40ea26c0c87e9becc8d)

## 版权放弃声明
Copyright and related rights waived via [CC0](https://github.com/ethereum/EIPs/blob/master/LICENSE.md)