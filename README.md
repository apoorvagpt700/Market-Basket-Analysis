# Overview
Market basket analysis is a data mining technique, generally used in the retail industry in an effort to understand purchasing behaviour. It looks for combinations of items that frequently occur in the same transaction. In other words, it gives insights into items that may have some association or affinity.

For example, customers purchasing flour and sugar are also likely to buy eggs. The outcome of the analysis is to derive a set of rules that can be understood as "if this, then that". Retailers can use these insights to do product placements or offer discounts.

In fact, market basket analysis is being applied outside retail. Therefore, it's more generally called Affinity Analysis.

## Examples of Market Basket Analysis

#### 1. Product placement
<ul> Identifying products that may often be purchased together and arranging the placement of those items (such as in a catalog or on a web site) close by to encourage the purchaser to buy both items. </ul>

#### 2. Physical shelf arrangement
<ul> An alternate use for physical product placement in a store is to separate items that are often purchased at the same time to encourage individuals to wander through the store to find what they are looking for to potentially increase the probability of additional impulse purchases. </ul>

#### 3. Up-sell, cross-sell, and bundling opportunities
<ul>  Companies may use the affinity grouping of multiple products as an indication that customers may be predisposed to buying the grouped products at the same time. This enables the presentation of items for cross-selling, or may suggest that customers may be willing to buy more items when certain products are bundled together. </ul>

#### 4. Customer retention
<ul> When customers contact a business to sever a relationship, a company representative may use market basket analysis to determine the right incentives to offer in order to retain the customer’s business. </ul>

## Association Rules
Data for market basket analysis typically comes from point-of-sale (POS) transaction data or invoices. These usually include list of products purchased, unit price and quantity of each item. Association analysis is a generalization of applications, like market basket analysis, and is now commonly applied in clickstream analysis, cross-selling recommendation engines, and information security. Association analysis is an unsupervised data science technique where there is no target variable to predict. Instead, the algorithm reviews each transaction containing a number of items (products) and extracts useful relationship patterns among the items in the form of rules. The challenge in association analysis is to differentiate a significant observation against unscrupulous rules. The Apriori and Frequent Pattern Growth algorithms offer efficient approaches to extract these rules from large datasets in the transaction logs.

An association is an expression of the form\
Body → head (support, confidence)
<br></br>
Following this form, an example of an association rule is the following:\
<br></br>
If a customer buys a flashlight, he/she will buy batteries (250, 81%).\
<br></br>
More than one dimension can be used to define the body portion of the association rule. For example, the rule might be expanded as the following:\
<br></br>
If a customer is a plumber and buys a flashlight, he/she will buy batteries (150, 89%).\



