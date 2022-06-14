# Getting Started with Google BERT

<a href="https://www.packtpub.com/product/getting-started-with-google-bert/9781838821593?utm_source=github&utm_medium=repository&utm_campaign=9781838821593"><img src="https://static.packt-cdn.com/products/9781838821593/cover/smaller" alt="Getting Started with Google BERT" height="256px" align="right"></a>

This is the code repository for [Getting Started with Google BERT](https://www.packtpub.com/product/getting-started-with-google-bert/9781838821593?utm_source=github&utm_medium=repository&utm_campaign=9781838821593), published by Packt.

**Build and train state-of-the-art natural language processing models using BERT**

## What is this book about?
BERT (bidirectional encoder representations from transformer) has revolutionized the world of natural language processing (NLP) with promising results. This book is an introductory guide that will help you get to grips with Google's BERT architecture. With a detailed explanation of the transformer architecture, this book will help you understand how the transformer’s encoder and decoder work.

You'll explore the BERT architecture by learning how the BERT model is pre-trained and how to use pre-trained BERT for downstream tasks by fine-tuning it for NLP tasks such as sentiment analysis and text summarization with the Hugging Face transformers library. As you advance, you’ll learn about different variants of BERT such as ALBERT, RoBERTa, and ELECTRA, and look at SpanBERT, which is used for NLP tasks like question answering. You'll also cover simpler and faster BERT variants based on knowledge distillation such as DistilBERT and TinyBERT. The book takes you through MBERT, XLM, and XLM-R in detail and then introduces you to sentence-BERT, which is used for obtaining sentence representation. Finally, you'll discover domain-specific BERT models such as BioBERT and ClinicalBERT, and discover an interesting variant called VideoBERT.

By the end of this BERT book, you’ll be well-versed with using BERT and its variants for performing practical NLP tasks.

This book covers the following exciting features: 
* Understand the transformer model from the ground up
* Find out how BERT works and pre-train it using masked language model (MLM) and next sentence prediction (NSP) tasks
* Get hands-on with BERT by learning to generate contextual word and sentence embeddings
* Fine-tune BERT for downstream tasks
* Get to grips with ALBERT, RoBERTa, ELECTRA, and SpanBERT models
* Get the hang of the BERT models based on knowledge distillation
* Understand cross-lingual models such as XLM and XLM-R
* Explore Sentence-BERT, VideoBERT, and BART

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1838821597) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders.

The code will look like the following:
```
(x_train, y_train), (x_test, y_test), preproc = text.texts_from_df(train_df = df,
                                                                   text_column = 'reviewText',
                                                                   label_columns=['sentiment'],
                                                                   maxlen=100,
                                                                   max_features=100000,
                                                                   preprocess_mode='bert',
                                                                   val_pct=0.1)

```

**Following is what you need for this book:**
This book is for NLP professionals and data scientists looking to simplify NLP tasks to enable efficient language understanding using BERT. A basic understanding of NLP concepts and deep learning is required to get the best out of this book. To get the most out of the book, run all the code provided in the book using Google Colab. 

With the following software and hardware list you can run all code files present in the book (Chapters 1, 2 and 5 do not contain code files).

### Software and Hardware List

| Chapter  | Software required                                                                                   | OS required                        |
| -------- | ----------------------------------------------------------------------------------------------------| -----------------------------------|
|    3     |   Google Colab / Python 3.x                                                                         | Windows, Mac OS X, and Linux (Any) |
|    4     |   Google Colab / Python 3.x                                                                         | Windows, Mac OS X, and Linux (Any) |
|    6     |   Google Colab / Python 3.x                                                                         | Windows, Mac OS X, and Linux (Any) |
|    7     |   Google Colab / Python 3.x                                                                         | Windows, Mac OS X, and Linux (Any) |
|    8     |   Google Colab / Python 3.x                                                                         | Windows, Mac OS X, and Linux (Any) |
|    9     |   Google Colab / Python 3.x                                                                         | Windows, Mac OS X, and Linux (Any) |


We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://static.packt-cdn.com/downloads/9781838821593_ColorImages.pdf).

## Errata

* Page 26 (Chapter 1, Learning position with positional encoding):
The formula should be:

<img src = "https://github.com/PacktPublishing/Getting-Started-with-Google-BERT/blob/main/Errata_images/chapter1_10000.PNG">

instead of 

<img src = "https://github.com/PacktPublishing/Getting-Started-with-Google-BERT/blob/main/Errata_images/chapter1_1000.png">

### Related products <Other books you may enjoy>
* Hands-On Python Natural Language Processing [[Packt]](https://www.packtpub.com/product/hands-on-python-natural-language-processing/9781838989590) [[Amazon]](https://www.amazon.com/dp/1838989595)

* The Applied AI and Natural Language Processing Workshop [[Packt]](https://www.packtpub.com/product/the-applied-ai-and-natural-language-processing-workshop/9781800208742) [[Amazon]](https://www.amazon.com/dp/B08Q8GNTGT)

## Get to Know the Author
**Sudharsan Ravichandiran** is a data scientist, researcher, bestselling author. He completed his Bachelor's in Information Technology at Anna University. His area of research focuses on practical implementations of deep learning and reinforcement learning, including Natural Language Processing and computer vision. He is an open-source contributor and loves answering questions on Stack Overflow. He also authored a best-seller, Hands-On Reinforcement Learning with Python, published by Packt Publishing.	
