# Layout-aware document preprocessing for RAG

RAG based systems are a powerful approach to extend the context of LLM requests with additional relevant information.
Just chunking the text of documents into sentences or paragraphs is not enough to maintain the full context of the information.

Looking at a research paper for example, it makes a huge difference if a sentence is under the "Related work" or "Results" section.

The goal of this demo is to show you some of the methods that you can use for preprocessing documents, so that you can improve the information retrieval process of RAG.

# What is Retrieval Augmented Generation RAG?
* Easy diagram, of RAG (paolo, search twitter for some of that)

# Why Layout aware document preprocessing?

# How to you use layout-aware document preprocessing on my case?

The main take aways are: 

* 0. Explore layout-aware document processing using [interactive Textract Demo in AWS Console](https://us-east-1.console.aws.amazon.com/textract/home?region=us-east-1#/demo) 
* 1. Utilize Langchain AmazonPDFLoader ([sample_notebook](01-langchain-textract.ipynb) 
* 2. [Amazon Textract Textractor Library](https://aws-samples.github.io/amazon-textract-textractor/index.html), [sample notebook](02-textractor.ipynb)
* 3. Textract API and AWS SDK

More complex examples:
* Asking questions on tabular data Notebook: example_01-qna-tabular-data .ipynb, [details](https://aws-samples.github.io/amazon-textract-textractor/notebooks/tabular_data_linearization_continued.html#)
* Converting PDF to HTML --> 02-textractor.ipynb
* Converting PDF to Markdown --> 02-textractor.ipynb
* TODO: take sm
webpages:
* Lanchain Playwright

## 1. Interactive Textract Demo in AWS console

Try the [interactive Textract Demo for layout analysis](https://us-east-1.console.aws.amazon.com/textract/home?region=us-east-1#/demo) in the AWS Console.
![alt text](images/layout_analysis_attention_page_0.png "Layout analysis of first page")

## 

Additional Resources

* [Deep dive into chunking of complex documents with layout analysis](https://github.com/aws-samples/layout-aware-document-processing-and-retrieval-augmented-generation/tree/main)