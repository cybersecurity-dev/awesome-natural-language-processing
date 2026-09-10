<div align="center">

```mermaid
mindmap
  root((NLP))

    Linguistics
      Morphology
      Syntax
      Semantics
      Pragmatics

    Preprocessing
      Tokenization
      Stemming
      Lemmatization
      Stopwords

    Representations
      Bag of Words
      TF-IDF
      Word2Vec
      GloVe
      FastText
      BERT

    Machine Learning
      Classification
      Clustering
      Regression

    Deep Learning
      RNN
      LSTM
      GRU
      Seq2Seq

    Transformers
      Attention
      Encoder
      Decoder
      BERT
      GPT
      T5

    Applications
      Translation
      Summarization
      Chatbots
      Search
      Question Answering
      RAG

    LLMs
      Prompt Engineering
      Fine Tuning
      RLHF
      Agents
```

# **`Awesome`** [NLP](https://wikipedia.org/wiki/Natural_language_processing) (_Natural Language Processing_) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
</div>

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtube.com/playlist?list=PL9V4Zu3RroiWzTYjmDxqtsfg38Fps4Hd4&si=3MVTWkspMjBhtLVQ)
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)]()

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefense"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

```mermaid
flowchart TD

A[Text]

A --> B[Bag of Words]
A --> C[N-Grams]
A --> D[TF-IDF]
A --> E[Word2Vec]
A --> F[GloVe]
A --> G[FastText]
A --> H[BERT Embeddings]

style B fill:#3498db,color:#fff
style D fill:#2ecc71,color:#fff
style H fill:#e74c3c,color:#fff
```

## 📖 Contents
- [My Other Awesome Lists](#my-other-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)


## Word Segmentation (_Tokenization_)

Tokenization is a text-processing technique that divides text into individual words or word fragments. This technique results in two key components: **`a word index`** and **`tokenized text`**. The word index is a list that maps unique words to specific numerical identifiers, and the tokenized text replaces each word with its corresponding numerical token. These numerical tokens are then used in various deep learning methods.


## Embedding Vector
* 🧠 What Does embedding_dim Mean?: The embedding_dim is the number of values in each word’s vector representation. So if:
    * `embedding_dim = 64` → each word is a 64‑dimensional vector
    * `embedding_dim = 128` → each word is a 128‑dimensional vector
    * `embedding_dim = 256` → each word is a 256‑dimensional vector

The embedding matrix size is: **`vocab_size × embedding_dim`**

##

### My Other Awesome Lists
You can access the my other awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/awesome-natural-language-processing/graphs/contributors)!

### License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

[🔼 Back to top](#awesome-nlp-natural-language-processing-)
