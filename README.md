## :hammer_and_wrench: CEKT

![The framework and details of CEKT.](images/CEKT%20framework.svg)

## :package: Dataset
The dataset statistics _**after preprocessing**_ are summarized as follows:
| **Name**   | **Students** | **Questions** | **KCs** | **KCs*** | **Interactions** | **Positive Label Rate** | **Avg. KCs per Q.** | **:link: Link** |
|:-----------|:----------------------:|:-------------:|:-------:|:--------:|:----------------:|:-----------------------:|:-------------------:|:---------------:|
| **BePKT**  | 762   | 305   | 70   | 156   | 75,613   | 85.75%   | 1.93 | [Download](https://drive.google.com/drive/folders/1U5u0rw3GT-n71D09DZqkhP1Fb5tlDcTb) |
| **Code-S** | 344   | 50    | 5    | 5     | 14,826   | 73.72%   | 1.00 | [Download](https://pslcdatashop.web.cmu.edu/Files?datasetId=3458) |
| **Code-F** | 494   | 50    | 5    | 5     | 23,703   | 74.15%   | 1.00 | [Download](https://pslcdatashop.web.cmu.edu/Files?datasetId=3458) |
| **Junyi**  | 6,000 | 278   | 36   | 36    | 265,267  | 82.48%   | 1.00 | [Download](https://pslcdatashop.web.cmu.edu/Files?datasetId=1198) |
| **POJ**    | 6,000 | 2,729 | –    | –     | 229,338  | 35.68%   | –    | [Download](https://drive.google.com/drive/folders/1LRljqWfODwTYRMPw6wEJ_%20mMt1KZ4xBDk) |


## :ledger: Baseline
| **Name** | **Title** | **:bookmark_tabs: Paper** | **:desktop_computer: Code** | **:classical_building: Venue** |
|:---------|:----------|:-------------------------:|:---------------------------:|:------------------------------:|
| **DKT** | Deep Knowledge Tracing | [Link](https://dl.acm.org/doi/10.5555/2969239.2969296) | [Link](https://github.com/chrispiech/DeepKnowledgeTracing) | NeurIPS'15 |
| **DKT+** | Addressing two problems in deep knowledge tracing via prediction-consistent regularization | [Link](https://dl.acm.org/doi/10.1145/3231644.3231647) | [Link](https://github.com/ckyeungac/deep-knowledge-tracing-plus) | L@S'18 |
| **DKVMN** | Dynamic Key-Value Memory Networks for Knowledge Tracing | [Link](https://dl.acm.org/doi/abs/10.1145/3038912.3052580) | Link | WWW'17 |
| **SAKT** | A Self-Attentive model for Knowledge Tracing | [Link](https://arxiv.org/abs/1907.06837) | Link | arXiv'19 |
| **AKT** | Context-Aware Attentive Knowledge Tracing | [Link](https://dl.acm.org/doi/abs/10.1145/3394486.3403282) | [Link](https://github.com/arghosh/AKT) | KDD'20 |
| **KQN** | Knowledge Query Network for Knowledge Tracing: How Knowledge Interacts with Skills | [Link](https://dl.acm.org/doi/abs/10.1145/3303772.3303786) | Link | LAK'19 |
| **SAINT** | Towards an Appropriate Query, Key, and Value Computation for Knowledge Tracing | [Link](https://dl.acm.org/doi/abs/10.1145/3386527.3405945) | Link | L@S'20 |
| **PEBG** | Improving Knowledge Tracing via Pre-training Question Embeddings | [Link](https://www.ijcai.org/proceedings/2020/0219.pdf) | [Link](https://github.com/ApexEDM/PEBG) | IJCAI'20 |
| **DIMKT** | Assessing Student's Dynamic Knowledge State by Exploring the Question Difficulty Effect | [Link](https://dl.acm.org/doi/abs/10.1145/3477495.3531939) | [Link](https://github.com/shshen-closer/DIMKT) | SIGIR'22 |
| **QIKT** | Improving Interpretability of Deep Sequential Knowledge Tracing Models with Question-centric Cognitive Representations | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/26661) | [Link](https://github.com/pykt-team/pykt-toolkit) | AAAI'23 |
| **ATDKT** | Enhancing Deep Knowledge Tracing with Auxiliary Tasks | [Link](https://dl.acm.org/doi/abs/10.1145/3543507.3583866) | [Link](https://github.com/pykt-team/pykt-toolkit) | WWW'23 |
| **simpleKT** | simpleKT: A Simple But Tough-to-Beat Baseline for Knowledge Tracing | [Link](https://openreview.net/pdf/d9869b82d0c8374bd652a9c12018e7a37a26ff2d.pdf) | [Link](https://github.com/pykt-team/pykt-toolkit) | ICLR'23 |
| **DTransformer** | Tracing Knowledge Instead of Patterns: Stable Knowledge Tracing with Diagnostic Transformer | [Link](https://dl.acm.org/doi/abs/10.1145/3543507.3583255) | [Link](https://github.com/yxonic/DTransformer) | WWW'23 |
| **FoLiBiKT** | Forgetting-aware Linear Bias for Attentive Knowledge Tracing | [Link](https://dl.acm.org/doi/abs/10.1145/3583780.3615191) | [Link](https://github.com/skewondr/FoLiBi) | CIKM'23 |
| **StableKT** | Enhancing Length Generalization for Attention Based Knowledge Tracing Models with Linear Biases | [Link](https://www.ijcai.org/proceedings/2024/0654.pdf) | [Link](https://github.com/pykt-team/pykt-toolkit) | IJCAI'24 |
| **FlucKT** | Cognitive Fluctuations Enhanced Attention Network for Knowledge Tracing | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/33562) | [Link](https://github.com/pykt-team/pykt-toolkit) | AAAI'25 |
| **LefoKT** | Rethinking and Improving Student Learning and Forgetting Processes for Attention based Knowledge Tracing Models | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/34998) | [Link](https://github.com/pykt-team/pykt-toolkit) | AAAI'25 |
| **RobustKT** | Enhancing Knowledge Tracing through Decoupling Cognitive Pattern from Error-Prone Data | [Link](https://dl.acm.org/doi/abs/10.1145/3696410.3714486) | [Link](https://github.com/pykt-team/pykt-toolkit) | WWW'25 |

## :cd: Installing Dependencies
<pre>
# cognitive_representation_module.ipynb (Colab is recommended)
pip install langchain langchain-openai langchain-deepseek langchain-qwq

# text_encoder.ipynb (Colab is recommended)
pip install openai pandas

# training
pip install -r requirements.txt
</pre>

## :bell: Attention
Currently, only the core **cognitive representation module** of CEKT has been open-sourced. The remaining components will be released after the paper is officially published. Thank you for your understanding and support.
