---
Topic:
    - 网络电商

License:
    - CC0 公共领域共享

Ext:
    - .xlsx
---

## **背景描述**
数据集包含了在2009年12月1日至2011年12月9日期间一家在英国已注册的非实体商店的在线零售的所有交易。该公司主要销售独特的各个场合均适用的礼品。这家公司的许多客户都是批发商。

## **数据说明**

**概览**

| 数据集记录数 | 数据集特征数量 | 有无缺失值 |
| -------- | -------- | -------- |
|1,067,371    | 8     | 有     |

**特征**

* InvoiceNo:发票号码，一个6位数的整数，唯一地分配给每个事件。如果此代码以字母“c”开头，则表示取消。
* StockCode: 产品(项目)代码。一个5位数的整数，唯一地分配给每个不同的产品。
* Description: 产品名称
* Quantity: 每笔交易每种产品(项目)的数量。
* InvoiceDate: 交易的日期和时间。
* UnitPrice: 单价，即产品单价(单位：英镑)。
* CustomerID: 客户编号，唯一分配给每个客户的5位整数。
* Country: 客户所在国家的名称。

## **数据来源**
Dr. Daqing Chen
课程主管: MSc Data Science. 
邮箱：*chend@lsbu.ac.uk*
地址：School of Engineering, London South Bank University, London SE1 0AA, UK.

## **问题描述**
属于商业领域的数据，适合Multivariate, Sequential, Time-Series, Text

使用该数据集的参考文献：
1. Chen, D. Sain, S.L., and Guo, K. (2012), Data mining for the online retail industry: A case study of RFM model-based customer segmentation using data mining, Journal of Database Marketing and Customer Strategy Management, Vol. 19, No. 3, pp. 197-208. 
2. Chen, D., Guo, K. and Ubakanma, G. (2015), Predicting customer profitability over time based on RFM time series, International Journal of Business Forecasting and Marketing Intelligence, Vol. 2, No. 1, pp.1-18.
3. Chen, D., Guo, K., and Li, Bo (2019), Predicting Customer Profitability Dynamically over Time: An Experimental Comparative Study, 24th Iberoamerican Congress on Pattern Recognition (CIARP 2019), Havana, Cuba, 28-31 Oct, 2019.
4. Laha Ale, Ning Zhang, Huici Wu, Dajiang Chen, and Tao Han, Online Proactive Caching in Mobile Edge Computing Using Bidirectional Deep Recurrent Neural Network, IEEE Internet of Things Journal, Vol. 6, Issue 3, pp. 5520-5530, 2019.
5. Rina Singh, Jeffrey A. Graves, Douglas A. Talbert, William Eberle, Prefix and Suffix Sequential Pattern Mining, Industrial Conference on Data Mining 2018: Advances in Data Mining. Applications and Theoretical Aspects, pp. 309-324. 2018.