# Bangla_MER: A Unique Dataset for Bangla Mathematical Entity Recognition

Welcome to the official repository of the **Bangla_MER Dataset**, a unique collection designed to advance mathematical entity recognition in the Bangla language. Our dataset addresses the scarcity of resources in this domain and serves as a stepping stone for further research and development.

## Introduction

Mathematical entity recognition in the Bangla language is an emerging field that lacks readily available datasets for training and evaluation. To address this gap, we present the **Bangla_MER Dataset**, comprising a total of 13,717 instances. Each instance includes a mathematical statement, its associated mathematical type, and the corresponding mathematical entity.

## Data Information

The **Bangla_MER Dataset** is meticulously structured to facilitate easy handling and seamless integration into deep learning and machine learning frameworks. It is provided in CSV format, featuring three columns:

| Text                          | Math Entity         | Label                 |
|-------------------------------|---------------------|-----------------------|
| যোগফল দ্বারা ৫              | যোগফল, ৫           | Operator, Number     |
| সম্পূর্ণ সংখ্যা            | সম্পূর্ণ সংখ্যা   | CMT                   |
| একটি মৌলিক সংখ্যা          | মৌলিক সংখ্যা     | CMT                   |
| তিনটি আদ্য সংখ্যা          | আদ্য সংখ্যা, তিন  | CMT, Number           |
| বিয়োগফলে দুটি সংখ্যা      | বিয়োগফল, সংখ্যা  | Operator, Number     |

The categorization process was driven by a thorough analysis of 3,430 diverse mathematical statements. By thoughtfully excluding certain raw data from direct categorization, we aimed to enhance the efficacy and real-time applicability of deep learning model training. The four categories derived from this process are: Numbers, Operators, Common Mathematical Terms (CMT), and Others.

This dataset serves as a valuable resource for researchers, practitioners, and enthusiasts seeking to explore mathematical entity recognition in the Bangla language. We believe that the **Bangla_MER Dataset** will stimulate advancements in this domain and contribute to the development of robust mathematical recognition models.

Feel free to explore, experiment, and contribute to the evolution of mathematical entity recognition with the Bangla_MER Dataset!
