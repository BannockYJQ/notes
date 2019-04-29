## Text summarization related paper

### 1. Abstractive Text Summarization using Sequence-to-sequence RNNs and Beyond
1. 使用用于翻译的encoder-decoder RNN方式
2. 使用新模型取得了相对较好的结果
3. 提供了一个衡量abstractive摘要的数据集
4. large vocabulary trick(LVT), Sébastien Jean, Kyunghyun Cho, Roland Memisevic, and Yoshua Bengio. 2014. On using very large target vocabulary for neural ma- chine translation. 
5. parts-of-speech tags, named-entity tags, tf and idf statistic of the words.
6. 使用switch来判断是否生成OOV
7. 两个级别的抽取，关键字级别和句子级别


### 2. Text Summarization Techniques: A Brief Survey
1. 关注于extractive summarization

### 3. The automatic creation of literature abstracts 
1. 基于统计、词表、以及词之间的位置，计算句子的重要程度

### 4. New Methods in Automatic Extracting 
1. 关键词（关键词字典），基于标题和首句，基于位置（首句，段落的开始）

### 5. Generic Text Summarization Using Relevance Measure and Latent Semantic Analysis
1. Standard IR method
2. The latent semantic methods.
3. Get the largest index of the k'th right singular value.

### 6. LexRank: Graph-based Lexical Centrality as Salience in Text Summarization
1. using graph and adjance matrix
2. Random walks on the sentence-based graphs can help in text summarization.
3.  We propose a graph representation of a document cluster, where vertices represent the sentences and edges are defined in terms of the similarity relation between pairs of sentences
4. Centrality of a sentence is often defined in terms of the
centrality of the words that it contains.
5. The centroid of a cluster is a pseudo-document which consists of words that have tf×idf scores above a predefined threshold
6. We hypothesize that the sentences that are similar to many of the other sentences in a cluster are more central (or salient) to the topic.

### Pretraining-Based Natural Language Generation for Text Summarization
```
bert --- info ----------          rst
          |            |           ^
          |            |           |
          |            |-----> transformer
          |                        ^
          v                        |
        transformer --------- > bert
```

### 2. QANet: Combining Local Convolution with Global Self-Attention for Reading Comprehension
