# Synapse-OpenAI

The Azure OpenAI service can be used to solve a large number of natural language tasks through prompting the completion API. To make it easier to scale your prompting workflows from a few examples to large datasets and integrated the Azure OpenAI service with the distributed machine learning library SynapseML. 
Besides this, some potential use cases for applying large language models at a distributed scale by using Azure OpenAI and Azure Synapse Analytics are:

- **Sentiment Analysis at Scale:** With Azure Synapse Analytics and Azure OpenAI, you can analyze sentiment of a large volume of text data such as customer reviews, social media posts, and support tickets. Azure Synapse Analytics provides a distributed SQL engine to query and join data from multiple sources, and you can use Azure OpenAI to apply pre-trained language models to classify each text document based on its sentiment.
- **Chatbot for Customer Service:** You can use Azure Synapse Analytics to store customer data and Azure OpenAI to build a chatbot that interacts with customers to answer their questions and resolve their issues. By using a large language model to power the chatbot, you can ensure that it can understand natural language and provide accurate responses.
- **Language Translation at Scale:** With Azure Synapse Analytics and Azure OpenAI, you can translate large volumes of text data from one language to another. You can store the source and target language text in Azure Synapse Analytics, use the distributed SQL engine to query and transform the data, and apply Azure OpenAI's pre-trained language models to perform the translation.
- **Text Summarization at Scale:** You can use Azure Synapse Analytics to store large volumes of text data, and use Azure OpenAI's large language models to summarize the text data into shorter, more manageable summaries. By using distributed computing to parallelize the text summarization process, you can handle large volumes of text data in a timely and efficient manner.
- **Text Analysis for Financial Services:** Azure Synapse Analytics can store and process large amounts of financial data such as stock prices, news articles, and social media sentiment. With Azure OpenAI, you can use pre-trained language models to perform sentiment analysis on the text data, identify relevant financial events, and even predict future market trends based on the analysis.

These are just a few examples of how you can apply large language models at a distributed scale using Azure OpenAI and Azure Synapse Analytics. With the power of distributed computing and pre-trained language models, the possibilities for analyzing and gaining insights from text data are almost limitless.

# Prerequisites
1. An Azure OpenAI Resourse
2. A Synapse Workspace
3. Create a serverless Apache Spark pool

Below you can find what you have to change and then, just run cell by cell. This is just an example and shows, how to apply large language models at a distributed scale using Azure Open AI and Azure Synapse Analytics.

The goal was to have one Notebook (inspired by SynapseML Library) that you can easily run and execute in your Synapse Workspace. Of course you can also load data directly form ADLS or other databases. For more information on loading and preparing Spark dataframes, have a look here: https://spark.apache.org/docs/latest/sql-data-sources.html

![image](https://user-images.githubusercontent.com/38947100/229354533-4eb48dae-e6d3-41b6-bcb1-9103a8c2841c.png).
