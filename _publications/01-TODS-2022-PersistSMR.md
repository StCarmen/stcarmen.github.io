---
title: "Persistent Summaries"
collection: publications
permalink: /publications/PersistSMR
excerpt: "A persistent summaries"
date: 2022-08-18
venue: "TODS"
year: 2022
paperurl: "https://dl.acm.org/doi/full/10.1145/3531053"
code: ""
authorlist: "Tianjing Zeng, Zhewei Wei, Ge Luo, Ke Yi, Xiaoyong Du, Ji-Rong Wen"
status: 'pub'
---
**Abstract:**

A persistent data structure, also known as a multiversion data structure in the database literature, is a data structure that preserves all its previous versions as it is updated over time. Every update (inserting, deleting, or changing a data record) to the data structure creates a new version, while all the versions are kept in the data structure so that any previous version can still be queried.
Persistent data structures aim at recording all versions accurately, which results in a space requirement that is at least linear to the number of updates. In many of today’s big data applications, in particular, for high-speed streaming data, the volume and velocity of the data are so high that we cannot afford to store everything. Therefore, streaming algorithms have received a lot of attention in the research community, which uses only sublinear space by sacrificing slightly on accuracy.
All streaming algorithms work by maintaining a small data structure in memory, which is usually called a sketch, summary, or synopsis. The summary is updated upon the arrival of every element in the stream, thus it is ephemeral, meaning that it can only answer queries about the current status of the stream. In this article, we aim at designing persistent summaries, thereby giving streaming algorithms the ability to answer queries about the stream at any prior time. 
