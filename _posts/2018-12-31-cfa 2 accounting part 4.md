---
layout: post
title: CFA Level 2 会计 Part 4
categories: CFA2级笔记
---

## 目录

1. 利润表和现金流量表的记录：退休后津贴（post-retirement plan）
2. 对于其他退休后给付办法（other post-retirement benefits）的会计处理
3. 分析师对于预计给付义务 / 约定给付义务的现值的处理
4. 股票类薪酬（share-based compensation）
5. 跨国经营（multinational operation）

<br><br>

## 1\. 利润表和现金流量表的记录：退休后津贴（post-retirement plan）
**备注：**US GAAP和IFRS在资产负债表的记录方式是<u>**不同的**</u>

<br><br>

### US GAAP的记录方式

**1\. 利润表**

US GAAP 在利润表上报告的退休后津贴支出被称为周期性养老金支出（periodic pension cost）

周期性养老金支出的计算过程

- (+) 负债项：预计给付义务的变化量（△PBO）：本期新增维护成本（current service cost）
- (+) 负债项：利息成本（interest cost）
- (+) 负债项：追溯性调整带来的维护成本的变化量（假设退休金计划发生了修改）（△past service cost (retrospective plan amendments)）
- (-) 资产项：退休基金的期望回报（expected return）
- (+) 资产项 + 负债项：摊销（amortization）→ 精算损益（actuarial gain / losses）

**2\. 现金流量表**

- (+) 未被摊销部分 → 精算损益（actuarial gain / losses）

追溯性调整带来的维护成本变化量（= 摊销）

- 这个变化量是固定的
- 追溯性调整带来的维护成本 / 员工的剩余在职时长（remaining service life）
  - 剩余在职时长 = 如果雇员一直工作到退休，还有多少年退休
- 本质上是在进行摊销，但注意别和精算损益的摊销混淆

精算损益（actuarial gain / losses）

- 注意此处精算损益是广义层面的，不仅仅包含【资产项：精算假设的变化】，还包含退休基金的预期和实际回报的差额
- 精算损益 =【资产项：退休基金的期望回报 - 实际回报】+ 【负债项：由于精算假设的变动带来的损失 / 收益】

精算损益的摊销

精算损益的摊销的原因

- 由周期性养老金支出的计算公式，可以看出，该项支出是每年是存在波动的，这个波动被记为精算损益
- 为了缓冲大幅度的波动，US GAAP允许公司对精算损益进行摊销

精算损益的摊销的计算方法

- 触发条件：当精算损益超出以下两者中的较大值的10%
  - 退休基金的期初公允价值
  - 年初预计给付义务
- 摊销的最低要求：通道法（corridor approach）
  - 使用直线摊销法，将超额部分平均地进行摊销，摊销的期限时长是用的是员工的剩余在职时长（remaining service life）
  - 剩余在职时长 = 如果雇员一直工作到退休，还有多少年退休
- 可以使用更快速的摊销
  - 但一旦使用不得随意修改

----

> ### 周期性养老金支出的分析 & 进一步解释
> 
> **a. 【周期性养老金支出】计算的基本原理**
> 
> - 理论上：公司每年的周期性养老金支出，是可以预测的
> - 实际上：公司每年的周期性养老金支出，会遇到多个因素的变化而发生波动
> - 可以理解为：每年公司实际的周期性养老金支出由两个部分构成
>  - <u>可准确预测部分 + 应波动而调整部分</u>
>
> **b. 【周期性养老金支出】的可准确预测部分**
> 
> - 从利润表科目【周期性养老金支出】的计算，可以看出前四项都是可以准确估测的
>   - 【负债项：预计给付义务的变化量：本期新增维护成本】
>   - 【负债项：利息成本】
>   - 【负债项：追溯性调整带来的维护成本的变化量（假设退休金计划发生了修改）】
>   - 【资产项：退休基金的（期望）收益率】
> 
> **c\. 【周期性养老金支出】的应波动而调整部分**
> 
> - 【周期性养老金支出】的第五项【 精算损益】就是对预测的调整
>
> 预测的调整，即，【精算损益】，是一下两个因素的总和
> 
> - 【资产项：退休基金的期望回报 - 实际回报】
>   - 受退休基金的投资收益业绩表现而影响
> - 【负债项：由于精算假设的变动带来的损失 / 收益】
>   - 因为自然灾害，经济周期，国民生活水平等因素而带来的员工寿命预期改变

----

### IFRS的记录方式

**1\. 利润表**

IFRS 在利润表上报告的退休后津贴支出也被称为周期性养老金支出（periodic pension cost）

- (+) 负债项：约定给付义务的现值的变化量（△PVDBO）：本期新增维护成本（service cost）
- (+) 资产项 + 负债项：净利息收入/支出（net interest income/expense）

**2\. 现金流量表**

- (+) 调整（remeasurement）
  - 属于投资性现金流

<br><br>

### IFRS和US GAAP的区别：

1\. 在IFRS中，本期新增维护成本（service cost）相当于以下US GAAP两项的组合，并且不再摊销，直接当即记为损益

- 【相似】(+) 负债项：约定给付义务的现值的变化量：本期新增维护成本
- 【改变】(+) 负债项：追溯性调整带来的维护成本的变化量（假设退休金计划发生了修改）
  - 与US GAAP不同，调整后的成本变化需当即记为损益，不能摊销

2\. 在IFRS中，净利息收入/支出（net interest expense）相当于以下US GAAP两项的组合，并且不再使用期望收益率，而是公司折现率

- 【相似】(+) 负债项：利息成本的变化量（△interest cost）
- 【改变】(-) 资产项：退休基金的“期望回报”（退休基金价值 × 折现率）
  - 期望收益率只允许使用公司的折现率，即PVDBO的折现率
- 所以具体是属于收入还是支出，取决于资金预备情况（funded status）
  - 如果退休基金的公允价值更高 > 约定给付义务的现值，就是收入，反之亦然

3\. 在IFRS中，调整（remeasurement）相当于US GAAP的精算损益（actuarial gain / losses），并且不再使用期望收益率，而是公司折现率，并且所有的调整直接计入投资性现金流

- 【相似】(+) 负债项：由于精算假设的变动带来的损失 / 收益
- 【改变】(-) 资产项 + 负债项：退休基金的“期望回报”（退休基金价值 × 折现率） - 实际回报
- 注意：
  - 收益率：不再使用退休基金的期望收益率，而是更保守的公司折现率
  - 所有的调整直接计入投资性现金流

4\. US GAAP的精算损益比IFRS的精算损益涵盖更广泛

- 在US GAAP中，精算损益除了包含精算假设的改变带来的损益，还包括养老基金的期望收益率和实际收益率之间的差额带来的损益

<br><br>

**公司必须披露关于预计给付义务 / 约定给付义务的现值的三个（或四个）基本假设（assumption）**

1. 折现率（discount rate）
  - 用于计算预计给付义务（projected benefit obligation）的折现率的现值
  - 这个利率的基准利率来自于本公司的具有相似期限特征的高质量公司固定收益产品（high quality corporate fixed income investments with a maturity profile similar to the future obligation）
2. 员工报酬增长率（rate of compensation growth）
3. 存在期限条件的给付义务的期望期限（expected vesting rate）
4. 仅限US GAAP：养老基金的期望收益率（expected return）

基本假设的改变带来的影响（effect）

- 折现率的提高
  - 预计给付义务 / 约定给付义务的现值降低，资金预备情况（funded status）改善
  - 常常也会减少利息支出，除非养老金应该开始正式运行提供年金
  - 周期性养老金支出也会降低，因为更低的本期新增维护成本（service cost）
- 工资增长率的降低
  - 未来需要支付的养老金额度降低，资金预备情况改善
  - 减少当前本期新增维护成本（current service cost），利息成本也下降，所以周期性养老金支出下降
- 仅限US GAAP：养老基金的期望收益率上升
  - 周期性养老金支出下降
  - 但是不影响预计给付义务的资金预备情况

<br><br>

## 2\. 对于其他退休后给付办法（other post-retirement benefits）的会计处理

以下假设变化会导致更高的给付义务 & 更高的周期支出

- 更高的短期（near-term）医疗费用通胀率
- 更高的长期医疗费用通胀率（ultimate health care trend rate）
- 需要多少年医疗费用会达到预测的长期通胀率水平？
  - 需要时间越长，给付义务和周期支出越高

<br><br>

## 3\. 分析师对于预计给付义务 / 约定给付义务的现值的处理

<br><br>

###1\.基本原则：

- 分析师需要考虑预计给付义务 / 约定给付义务的现值的四个假设（上文提及过）
  - 折现率
  - 预计公司增长率
  - 医疗费用的通胀率
  - 养老基金的期望收益率
- 分析师应该从这些角度评估这些假设：
  - 和其他公司的对比
  - 在不同经济环境下的变化
  - 和过去相比发生的变化

### 2\. 利润表的处理

分析师倾向于对利润表科目周期性养老金支出（periodic pension cost）进行调整，这个调整后的项目被称为总 / 净周期性养老金支出（total / net periodic pension cost）

- 目的：反映周期性养老金支出（periodic pension cost）的公允价值
  - 因为在会计报表中，一部分支出出现在了现金流量表中（投资性现金流）
- 计算方法1：=（年终资金预备情况 - 年初资金预备情况）- 雇主出资额（employer‘s contribution）
  - 资产是正数，负债是负数
  - 算出的结果如果为正，净养老金收入，如果为负，净养老金支出
- 计算方法2：= 实际收益 - 预计给付义务的四个增加项
  - 四个增加项：本期新增维护成本 + 利息支出 + 追溯性调整 + 精算损益
  - 两个公式本质是一样的，只是描述方式不同

- 过去被称为经济养老金费用 / 支出（economic pension expense / cost）

**养老支出的再分级（reclassify pension expense）**

目的：将养老金的收入和支出并入公司的利润表中

- 收入：actual return
- 支出：current service cost + interest cost + expected return + actuarial GL

具体步骤：

1. 将养老金支出加回营业利润（operating profit）
2. 从调整后的营业利润减去本期新增维护成本（current service cost）
3. 将养老金的利息支出计入利润表的利息支出
4. 将养老基金的实际收益计入非主营业务收入（non-operating income）



### 3\. 现金流量表的处理

唯一会影响公司现金的因素是雇主出资额（employer contribution）
- 剩下的因素：雇员利益给付（benefits paid），利息成本等，都属于养老基金的支出，而养老基金不属于公司

分析师的现金流量表分析：

- 关于养老金支出的现金流量情况分为两种情况：
  - 出资过剩（overcontribution）：雇主出资额 > 总养老金支出
  - 出资不足（undercontribution）：雇主出资额 < 总养老金支出

> 注意区别公司财务报表中关于资金预备情况的两个概念：

> - 资金预备不足（underfunded）：资产负债表上以负债项 净待预备给付义务（net underfunded pension obligation）记录差额
> - 准备剩余过剩（overfunded）：资产负债表上以资产项 净超额预备给付义务（net overfuned pension obligation）

出资不足：

- 相当于公司向员工借贷
- adjusted CFO = CFO - (total periodic pension cost - contribution ) × ( 1 - tax rate)
- adjusted CFF = CFF + (total periodic pension cost - contribution ) × ( 1 - tax rate)

出资过剩：

- adjusted CFO = CFO + (total periodic pension cost - contribution ) × ( 1 - tax rate)
- adjusted CFF = CFF - (total periodic pension cost - contribution ) × ( 1 - tax rate)

## 4\. 股票类薪酬（share-based compensation）

<br><br>

有四种股票类薪酬（share-based compensation）

- 权益交割类（equity settled）
  - 股权（stock option）
  - 无偿配股（stock grants）
- 现金交割类（cash settled）
  - 股票升值权（stock appreciation rights）
  - 虚拟股票（phantom shares）

股票类薪酬的缺点

1. 提供的激励不一定有效，因为业绩不一定能影响股价（influence market value）
2. 可能会改变风险承受能力，变得更加风险厌恶（risk adverse） / 风险偏好（risk seeking）
3. 稀释（dilute）股东股份

**1\. 股权（stock option）**

看涨期权（call option）

- 实值（in-the-money）期权
- 虚值（out-of-the-money）期权

存在期限条件的（vesting date）的期权

**2\. 无偿配股（stock grants）**

公司可以通过以下两种方式获得将要提供给雇员的股票：

1. 股票增发
  - 会增加资本公积（additional paid-in capital）
2. 股票回购

**3\. 股票升值权（stock appreciation rights）**

- 适用于上市公司
- 薪酬支出将会被平摊至雇员的在职周期上（allocated over the service period）

**4\. 虚拟股票（phantom shares）**

- 适用于非上市公式
- 相当于虚拟的股票升值权
- 依照一些指标，假设一个股价

<br><br>

## 5\. 跨国经营（multinational operation）

<br><br>

海外经营的财务报表折算（translation of foreign operation）

货币的三种分类：

1. 区域货币（local currency）（ ≠ 公司本国货币）
  - 子公司运营所在地的货币
2. 功能性货币（functional currency）
  - 公司的现金流主要产生的货币
3. 报告 / 呈现用货币（reporting currency / presentation currency）
  - 母公司用于财务报表报告用途的货币单位

**外币折算的两种主要方法：**

1. 现行汇率法（current rate method）
    - 使用制表时最新的汇率
2. 时态法（temporal method）
    - 追溯历史汇率

**外币折算的两种类型：**

1. 调整（remeasurement）
2. 折算（狭义）（translation）

> 注意不要混淆：

> - 折算方法和折算类型是两个概念
> - 简单来说，每个折算类型，使用的折算方法的方式会有差异，具体在操作方式在下面详细介绍

两种类型具体使用的步骤：

1. 判断：本地货币 = 功能性货币？
  - 如果不同，进行调整（remeasurement），然后进行步骤2
  - 如果相同，直接进行步骤2
2. 判断：功能性货币 = 报告用货币？
  - 如果不同，进行折算（狭义）（translation）
  - 如果相同，直接报告结果
3. （如果同时进行了调整和折算（狭义），则统称为折算（广义））

**两种折算方法的对比**

1\. 在资产负债表中：

- 货币性资产 / 负债（monetary assets / liabilities）
  - 时态法：现行汇率
  - 现行法：现行汇率
- 非货币性资产 / 负债（non-monetary assets / liabilities）
  - 时态法：历史汇率
  - 现行法：现行汇率
- 股东原始出资（capital）（= 实收资本（actual receipt capital / paid-in capital）+ 资本公积（additional paid in capital））
  - 时态法：历史汇率
  - 现行法：历史汇率
- 保留盈余（retained earning）
  - 时态法：平衡（既不是历史汇率，也不是现行汇率，而是为了配平资产负债表而计算出的值）
  - 现行法：平衡（同时态法）
- 权益（总体来说）
  - 时态法：不确定
  - 现行法：现行汇率（因为资产和负债都是现行汇率）

（实际上，绝大多数负债都是属于货币性，常见的例外是预收收入（unearned revenue））

在利润表中：

- 主营业务收入以及其他支出（sales and other expenses）
  - 时态法：平均值
  - 现行法：平均值
- 主营业务支出（cost of goods sold）
  - 时态法：历史汇率
  - 现行法：平均值
- 折旧（depreciation）
  - 时态法：历史汇率
  - 现行法：平均值
- 总收入以及其他支出（revenue and other expenses）
  - 时态法：平均值
  - 现行法：平均值
- 外汇折算损益（translation gains/losses）
  - 时态法：进行再测量（remeasurement），在利润表上确认（recognized on income statement），影响保留盈余（retained earning），但不影响累计换算调整数（cumulative translation adjustment）
  - 现行法：进行折算（狭义）（translation），在资产负债表上的权益中确认（recognized in equity），影响累计换算调整数
