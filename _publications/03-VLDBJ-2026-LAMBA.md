---
title: "Lamba: A Pretrained Model for Latency Prediction over Distributed Databases"
collection: publications
permalink: /publications/LAMBA
excerpt: "A pretrained latency prediction model for distributed databases"
date: 2026-03-01
venue: "VLDBJ"
year: 2026
paperurl: ""
code: ""
authorlist: "Yingli Zhou*, Tianjing Zeng*, Rong Zhu, Yingze Li, Junwei Lan, Zhewei Wei, Yixiang Fang, Bolin Ding, Jingren Zhou"
status: 'pub'
---
**Abstract:**

Latency prediction is crucial for databases, yet traditional methods lack accuracy while machine learning based approaches demand heavy overheads on data collection and model training. Existing zero-shot methods leverage pretraining to attain cross-database generality but primarily focus on centralized databases, overlooking the distributed databases widely used for processing large-scale data. Distributed databases with multiple segment nodes bring additional challenges for latency prediction, including the varying data distributions across segments, the inter-segment data migration during execution, heterogeneous environments and etc.
To tackle these challenges, we introduce Lamba, a pretrained \underline{m}odel tailored for \underline{la}tency prediction and aligning with the inherent characteristics of distributed data\underline{ba}ses. It employs low-level and transferable features and a dual-stage design mirroring query execution. Specifically, the \emph{Segment Encoder} captures specific execution patterns on each segment node and the \emph{Inter-Segment Interactor} models inter-segment interactions.  In such way, Lamba naturally learns the intricate relations among these features, captures the \emph{meta-knowledge} actually matters to latency prediction and generalizes across diverse data, queries, and environments. Pretrained on execution statistics from 30 diverse datasets deployed on Alibaba AnalyticDB, Lamba delivers superior accuracy on unseen datasets with a compact model size of only $3.39$MB. It can be further improved with finetuning and adapts seamlessly to various, sometimes totally new, scenarios, including but not limited to data updating and scaling, workload drifts and environment changes.
