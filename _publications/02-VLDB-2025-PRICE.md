---
title: "PRICE: A Pretrained Model for Cross-Database Cardinality Estimation"
collection: publications
permalink: /publications/PRICE
excerpt: "PRICE: A Pretrained Model for Cross-Database Cardinality Estimation"
date: 2025-09-01
venue: "VLDB"
year: 2025
code: "https://github.com/StCarmen/PRICE"
paperurl: https://github.com/StCarmen/PRICE/blob/master/PRICE_full_paper.pdf
authorlist: "Tianjing Zeng, Junwei Lan, Jiahong Ma, Wenqing Wei, Rong Zhu, Pengfei Li, Bolin Ding, Defu Lian, Zhewei Wei, Jingren Zhou"
status: 'pub'
---
**Abstract:**

Cardinality estimation (CardEst) is essential for optimizing query execution plans. Recent ML-based CardEst methods achieve high accuracy but face deployment challenges due to high preparation costs and lack of transferability across databases. In this paper, we propose PRICE, a PRetrained multI-table CardEst model, which addresses these limitations. PRICE takes low-level but transferable features w.r.t. data distributions and query information and elegantly applies self-attention models to learn meta-knowledge to compute cardinality in any database. It is generally and adaptively applicable to any unseen new database to attain high estimation accuracy, while its preparation cost is as little as the basic onedimensional histogram-based CardEst methods. Moreover, PRICE can be finetuned to further enhance its performance on any specific database. We pretrained PRICE using 30 diverse datasets, completing the process in about 5 hours with a resulting model size of only about 40MB. Evaluations show that PRICE consistently outperforms existing methods, achieving the highest estimation accuracy on several unseen databases and generating faster execution plans with lower overhead. After finetuning with a small volume of database-specific queries, PRICE could even find plans that were very close to the optimal ones. Meanwhile, PRICE is generally applicable to different settings such as data updates, data scaling, and query workload shifts.
