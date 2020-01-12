# 预训练语言模型
[toc]

## 模型

#### [2017 attention is all you need]()
- https://arxiv.org/pdf/1706.03762.pdf
#### [201801 Universal Language Model Fine-tuning for Text Classification](resources/notes/d0001/pretrainlm_201801_Universal_Language_Model_Fine_tuning_for_Text_Classification.md)
https://arxiv.org/pdf/1801.06146.pdf
![](resources/images/d0001/522002251607201.png)
- 训练双向LM，采用多任务训练方式
- 特殊的学习率实现：1) 逐层降低学习率, 2) 倾斜的三角学习率
- 逐层解冻

#### [2018 ACL Deep contextualized word representations: ELMO](resources/notes/d0001/pretrainlm_2018_deep_contextualized_word_representations.md)
- https://arxiv.org/pdf/1802.05365.pdf

#### [Massively Multilingual Sentence Embeddings for Zero-Shot Cross-Lingual Transfer and Beyond（Facebook/2018）]

#### [MASS: Masked Sequence to Sequence Pre-training for Language Generation（Microsoft/2019）]

#### 【Multi-Task Deep Neural Networks for Natural Language Understanding（Microsoft/2019）

#### 


#### [Unified Language Model Pre-training for Natural Language Understanding and Generation（Microsoft/2019）]

#### [201904 ERNIE: Enhanced Representation through Knowledge Integration](resources/notes/d0001/pretrainml_201904_ERNIE__Enhanced_Representation_through_Knowledge_Integration.md)
- https://arxiv.org/pdf/1904.09223v1.pdf
- 命名实体、词组mask，以及DLM数据扩充
![](resources/images/d0001/01301020300201420203.png)
![](resources/images/d0001/01301510300201445103.png)
![](resources/images/d0001/01301160300201511603.png)

#### [ERNIE: Enhanced Language Representation with Informative Entities（THU/ACL2019）]

#### [Cross-lingual Language Model Pretraining（Facebook/2019）]

#### [201906 RoBERTa: A Robustly Optimized BERT Pretraining Approach](resources/notes/d0001/pretrainlm_201907_RoBERTa__A_Robustly_Optimized_BERT_Pretraining_Approach.md)
- https://arxiv.org/abs/1907.11692
- 特点
    - 更大数据，更大的batch size
    - 动态地改变应用于训练数据的遮蔽模式
    - 删除下一句预测目标(NSP)
    - 当采用 bytes-level 的 BPE 之后，编码任何输入文本而不会引入 UNKOWN 标记。

#### [201907 ERNIE 2.0: A Continual Pre-Training Framework for Language Understanding](resources/notes/d0001/pretrainml_201907_ERNIE_2.0__A_Continual_Pre_Training_Framework_for_Language_Understanding.md)
- https://arxiv.org/pdf/1907.12412
![](resources/images/d0001/01201210223207082102.png)
![](resources/images/d0001/01201230223207172302.png)


####  [2020 ELECTRA: Pre-training Text Encoders as Discriminators Rather Than Generators](resources/notes/d0001/pretrainlm_2020_ELECTRA__Pre-training_Text_Encoders_as_Discriminators_Rather_Than_Generators.md)
- https://openreview.net/pdf?id=r1xMH1BtvB



## 应用
