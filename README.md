# Knowledge-Graph-Construction-and-Visualization
Knowledge Graph Construction in Finance
## Step 1:数据爬取
使用selenium从九方智投上爬取股票相关数据并以csv文件格式保存，表格包括股票基础数据、股东数据、基金持股数据、股票概念数据、股票公告数据。
## Step 2:金融知识图谱构建与可视化
基于Neo4j对爬取后的数据组织成知识图谱，并可视化呈现。 Neo4j是一个高性能的NoSQL图形数据库，它将结构化数据存储在网络上而不是表中，具有嵌入式、高性能、轻量级等优势。

示例：创建实体![image](https://github.com/user-attachments/assets/98ebfa01-7244-4820-8798-bcd08697fd51)

示例：创建关系![image](https://github.com/user-attachments/assets/e61af50d-a30d-4bc4-b14d-e775e70b646f)

## Step 3:图数据的查询和更新
Cypher是一种声明式图数据库查询语言，能高效地查询和更新图数据，借鉴了SQL语言的结构。

示例：查询某股票![image](https://github.com/user-attachments/assets/3c2fed9e-62a8-4fca-8fae-5218dde4bbff)
