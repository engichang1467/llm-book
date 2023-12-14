# Introduction to Large Language Models

<a href="https://www.amazon.co.jp/o/ASIN/4297136333/"><img src="misc/cover-small.png" width="200"></a>

This is the English version repository for "Introduction to Large Language Models" (Gijutsu-Hyohron Co., Ltd., 2023).

## Code

All code has been tested to work on Google Colaboratory.
The datasets used in the code and the models created are available on the [Hugging Face Hub](https://huggingface.co/llm-book).

**⚠️ As of July 28, 2023, the link to the source of the MARC-ja dataset is broken, and there is an error in loading the dataset in the code sections 5.2, 5.3, 5.5.4 in the book.
We have sent an inquiry email and are currently waiting for recovery.**

**In response to this, we have added a notebook using the Japanese sentiment analysis dataset [WRIME](https://github.com/ids-cv/wrime). Please utilize it if you want to run the code.**



| Chapter                                      | Section/Item                                                                                                                | Colab                                                                                                                                                                                                 | Link                                                                                                      |
| --------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| Chapter 1 Introduction                        | 1.1 Solve natural language processing with transformers<br />1.2 Basic usage of transformers                               | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/engichang1467/llm-book-english/blob/english-translate/chapter1/1-introduction.ipynb)                    | [Link](https://github.com/engichang1467/llm-book-english/blob/english-translate/chapter1/1-introduction.ipynb)                    |
| Chapter 2 Transformer                         | 2.2 Encoder                                                                                                                 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/engichang1467/llm-book-english/blob/english-translate/chapter2/2-2-transformer-position-encoding.ipynb) | [Link](https://github.com/engichang1467/llm-book-english/blob/english-translate/chapter2/2-2-transformer-position-encoding.ipynb) |
| Chapter 3 Fundamentals of Large Language Models | 3.2 GPT (Decoder)<br />3.3 BERT・RoBERTa (Encoder)<br />3.4 T5 (Encoder-Decoder)                                            | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/engichang1467/llm-book-english/blob/english-translate/chapter3/3-zero-shot-inference.ipynb)             | [Link](https://github.com/engichang1467/llm-book-english/blob/english-translate/chapter3/3-zero-shot-inference.ipynb)             |
|                                               | 3.6 Tokenization                                                                                                            | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/engichang1467/llm-book-english/blob/english-translate/chapter3/3-6-tokenization.ipynb)                  | [Link](https://github.com/engichang1467/llm-book-english/blob/english-translate/chapter3/3-6-tokenization.ipynb)                  |
| Chapter 5 Fine-tuning of Large Language Models | 5.2 Implementation of Sentiment Analysis Model                                                                              | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/engichang1467/llm-book-english/blob/english-translate/chapter5/5-2-sentiment-analysis-finetuning.ipynb) <br /> [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/engichang1467/llm-book-english/blob/english-translate/chapter5/5-2-sentiment-analysis-finetuning-wrime.ipynb) | [Link (MARC-ja)](https://github.com/engichang1467/llm-book-english/blob/english-translate/chapter5/5-2-sentiment-analysis-finetuning.ipynb) <br /> [Link (WRIME)](https://github.com/engichang1467/llm-book-english/blob/english-translate/chapter5/5-2-sentiment-analysis-finetuning-wrime.ipynb) |
|                                               | 5.3 Error Analysis of Sentiment Analysis Model                                                                              | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/engichang1467/llm-book-english/blob/english-translate/chapter5/5-3-sentiment-analysis-analysis.ipynb) <br /> [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/engichang1467/llm-book-english/blob/english-translate/chapter5/5-3-sentiment-analysis-analysis-wrime.ipynb)     | [Link (MARC-ja)](https://github.com/engichang1467/llm-book-english/blob/english-translate/chapter5/5-3-sentiment-analysis-analysis.ipynb) <br /> [Link (WRIME)](https://github.com/engichang1467/llm-book-english/blob/english-translate/chapter5/5-3-sentiment-analysis-analysis-wrime.ipynb)     |
|                                               | 5.4.1 Implementation of Natural Language Inference (Training)                                                               | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/engichang1467/llm-book-english/blob/english-translate/chapter5/5-4-nli-finetuning.ipynb)                 | [Link](https://github.com/engichang1467/llm-book-english/blob/english-translate/chapter5/5-4-nli-finetuning.ipynb)                 |
|                                               | 5.4.1 Implementation of Natural Language Inference (Analysis)                                                               | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/engichang1467/llm-book-english/blob/english-translate/chapter5/5-4-nli-analysis.ipynb)                 | [Link](https://github.com/engichang1467/llm-book-english/blob/english-translate/chapter5/5-4-nli-analysis.ipynb)                 |
|                                               | 5.4.2 Implementation of Semantic Similarity Calculation (Training)                                                         | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/engichang1467/llm-book-english/blob/english-translate/chapter5/5-4-sts-finetuning.ipynb)                 | [Link](https://github.com/engichang1467/llm-book-english/blob/english-translate/chapter5/5-4-sts-finetuning.ipynb)                 |
|                                               | 5.4.2 Implementation of Semantic Similarity Calculation (Analysis)                                                         | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/engichang1467/llm-book-english/blob/english-translate/chapter5/5-4-sts-finetuning.ipynb)                 | [Link](https://github.com/engichang1467/llm-book-english/blob/english-translate/chapter5/5-4-sts-analysis.ipynb)                 |
|                                               | 5.4.3 Implementation of Multiple-Choice Question Answering Model (Training)                                                | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/engichang1467/llm-book-english/blob/english-translate/chapter5/5-4-multiple-choice-qa-finetuning.ipynb)       | [Link](https://github.com/engichang1467/llm-book-english/blob/english-translate/chapter5/5-4-multiple-choice-qa-finetuning.ipynb)       |
|                                               | 5.4.3 Implementation of Multiple-Choice Question Answering Model (Analysis)                                                | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/engichang1467/llm-book-english/blob/english-translate/chapter5/5-4-multiple-choice-qa-analysis.ipynb)       | [Link](https://github.com/engichang1467/llm-book-english/blob/english-translate/chapter5/5-4-multiple-choice-qa-analysis.ipynb)       |
|                                               | 5.5.4 LoRA Tuning (Sentiment Analysis)                                                                                      | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ghmagazine/llm-book/blob/main/chapter5/5-5-sentiment-analysis-finetuning-LoRA.ipynb) <br /> [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ghmagazine/llm-book/blob/main/chapter5/5-5-sentiment-analysis-f) | [Link (MARC-ja)](https://github.com/ghmagazine/llm-book/blob/main/chapter5/5-5-sentiment-analysis-finetuning-LoRA.ipynb) <br /> [Link (WRIME)](https://github.com/ghmagazine/llm-book/blob/main/chapter5/5-5-sentiment-analysis-finetuning-LoRA-wrime.ipynb) |
| Chapter 6 Named Entity Recognition              | 6.2 Dataset, Preprocessing, and Evaluation Metrics<br />6.3 Implementation of Named Entity Recognition Models<br />6.4 Building Datasets Using Annotation Tools              | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ghmagazine/llm-book/blob/main/chapter6/6-named-entity-recognition.ipynb)        | [Link](https://github.com/ghmagazine/llm-book/blob/main/chapter6/6-named-entity-recognition.ipynb)        |
| Chapter 7 Summary Generation                    | 7.2 Dataset<br />7.3 Evaluation Metrics<br />7.4 Implementation of Headline Generation Models<br />7.5 Headline Generation by Various Methods                              | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ghmagazine/llm-book/blob/main/chapter7/7-summarization-generation.ipynb)        | [Link](https://github.com/ghmagazine/llm-book/blob/main/chapter7/7-summarization-generation.ipynb)        |
| Chapter 8 Sentence Embedding                    | 8.3 Implementation of Sentence Embedding Models                                                                             | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ghmagazine/llm-book/blob/main/chapter8/8-3-simcse-training.ipynb)               | [Link](https://github.com/ghmagazine/llm-book/blob/main/chapter8/8-3-simcse-training.ipynb)               |
|                                                | 8.4 Search Using the Nearest Neighbor Library `Faiss`                                                                       | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ghmagazine/llm-book/blob/main/chapter8/8-4-simcse-faiss.ipynb)                  | [Link](https://github.com/ghmagazine/llm-book/blob/main/chapter8/8-4-simcse-faiss.ipynb)                  |
| Chapter 9 Question Answering                    | 9.3 Making ChatGPT Answer Quizzes                                                                                            | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ghmagazine/llm-book/blob/main/chapter9/9-3-quiz-chatgpt.ipynb)                  | [Link](https://github.com/ghmagazine/llm-book/blob/main/chapter9/9-3-quiz-chatgpt.ipynb)                  |
|                                                | 9.4.3 Implementation of BPR                                                                                                 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ghmagazine/llm-book/blob/main/chapter9/9-4-3-bpr-training.ipynb)                | [Link](https://github.com/ghmagazine/llm-book/blob/main/chapter9/9-4-3-bpr-training.ipynb)                |
|                                                | 9.4.4 Calculation of Passage Embeddings with BPR                                                                            | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ghmagazine/llm-book/blob/main/chapter9/9-4-4-bpr-embedding.ipynb)               | [Link](https://github.com/ghmagazine/llm-book/blob/main/chapter9/9-4-4-bpr-embedding.ipynb)               |
|                                                | 9.5 Combining Document Search Models and ChatGPT                                                                            | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ghmagazine/llm-book/blob/main/chapter9/9-5-quiz-chatgpt-plus-bpr.ipynb)         | [Link](https://github.com/ghmagazine/llm-book/blob/main/chapter9/9-5-quiz-chatgpt-plus-bpr.ipynb)         |


## Errata

The errata for this book are published on the following page.

[https://github.com/ghmagazine/llm-book/wiki/errata](https://github.com/ghmagazine/llm-book/wiki/errata)

## Links

- [Hugging Face Hub](https://huggingface.co/llm-book)
- [Gijutsu-Hyohron Co., Ltd. page](https://gihyo.jp/book/2023/978-4-297-13633-8)
- [Amazon.co.jp](https://www.amazon.co.jp/o/ASIN/4297136333/)