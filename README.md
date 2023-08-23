# Bangla_MER: A Unique Dataset for Bangla Mathematical Entity Recognition

Welcome to the official repository of the **Bangla_MER Dataset**, a unique collection designed to advance mathematical entity recognition in the Bangla language. Our dataset addresses the scarcity of resources in this domain and serves as a stepping stone for further research and development.

## Introduction

Mathematical entity recognition in the Bangla language is an emerging field that lacks readily available datasets for training and evaluation. To address this gap, we present the **Bangla_MER Dataset**, comprising a total of 13,717 instances. Each instance includes a mathematical statement, its associated mathematical type, and the corresponding mathematical entity.

## Data Information

The **Bangla_MER Dataset** is meticulously structured to facilitate easy handling and seamless integration into deep learning and machine learning frameworks. It is provided in CSV format, featuring three columns:

### Data Example

| Text                          | Math Entity         | Label                 |
|-------------------------------|---------------------|-----------------------|
| এক আর দুই যোগ করলে তিন হবে।              | এক, দুই, তিন           | Number     |
| ঋণাত্মক সংখ্যার বর্গমূল হল যৌগিক সংখ্যা।           | বর্গমূল   | Operator       |
| এক কোনো মৌলিক সংখ্যা নয়।         | মৌলিক সংখ্যা     | Common Mathematical Terms    |
| সাত থেকে পাঁচ বিয়োগ করলে দুই হবে । | থেকে করলে হবে | Others |  


The categorization process was driven by a thorough analysis of 3,430 diverse mathematical statements. By thoughtfully excluding certain raw data from direct categorization, we aimed to enhance the efficacy and real-time applicability of deep learning model training. The four categories derived from this process are: Numbers, Operators, Common Mathematical Terms (CMT), and Others.

This dataset serves as a valuable resource for researchers, practitioners, and enthusiasts seeking to explore mathematical entity recognition in the Bangla language. We believe that the **Bangla_MER Dataset** will stimulate advancements in this domain and contribute to the development of robust mathematical recognition models.

Feel free to explore, experiment, and contribute to the evolution of mathematical entity recognition with the Bangla_MER Dataset!
