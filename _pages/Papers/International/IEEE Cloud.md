---
title: "Carbon-Aware and Fault-Tolerant Migration of Deep Learning Workloads in the Geo-distributed Cloud"
tags:
    - IEEE CLOUD 2024
    - accepted rate 19.4%
    - Top tier
    - CONF paper
date: "2024-06-03"
thumbnail: "/assets/img/news/cloud.png"
bookmark: true
---

<figure> 
    <img src="/assets/img/paper/IEEE CLOUD.png" alt="IEEE CLOUD" style="width:378px; height:293px;"> -->
    <figcaption align='center'>The Overview of the proposed method(CAFTM)</figcaption>
</figure>


# Paper information
Carbon-Aware and Fault-Tolerant Migration of Deep Learning Workloads in the Geo-distributed Cloud
**Jeonghyeon Park**, Daero Kim, Jiseon Kim, Jungkyu Han, Sejin Chun (2024). IEEE International Conference on Cloud Computing (CLOUD)


## Keywords
carbon-aware, fault-tolerant, geo-distributed, cloud, deep learning, task migration


## Abstract
Recently, many deep learning models have been trained in geographically distributed data centers. The carbon emissions produced by training the models may pose a significant threat to climate change like increasing temperatures. Existing studies have a hardship in shifting the workload of training models to a data center with low carbon emissions. So, they fail to ensure low emissions of the workload during training, especially when long-term workloads like Large Language Models (LLMs) are trained. To cope with this problem, we propose a method that shifts the workload to a cloud with low carbon emissions while enduring a lack of computational resources. Specifically, we define a task scheduler that includes states and their transitions to migrate mini-batches dynamically. Next, we present a fault-tolerant control that optimizes a GPU frequency to adapt to workload variations of training models while guaranteeing its power consumption. Last, we conducted exhaustive experiments using real-world data in terms of carbon emissions, transfer time, and power consumption compared to state-of-the-art methods.

## Cite
~~~
@INPROCEEDINGS{10643899,
  author={Park, Jeonghyeon and Kim, Daero and Kim, Jiseon and Han, Jungkyu and Chun, Sejin},
  booktitle={2024 IEEE 17th International Conference on Cloud Computing (CLOUD)}, 
  title={Carbon-Aware and Fault-Tolerant Migration of Deep Learning Workloads in the Geo-Distributed Cloud}, 
  year={2024},
  pages={494-501},
  }
~~~

