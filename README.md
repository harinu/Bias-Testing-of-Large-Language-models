# Bias-Testing-of-Large-Language-models

Natural Language Processing (NLP) has experienced a rapid increase in the development and deployment of large language models (LLMs). These models have the capability to generate text and interact with
users in the form of a dialogue. Currently, many companies rely on these models to solve various tasks. However, studies have revealed that large pre-trained language models exhibit biases against social groups based
on race, gender, religion, etc. These biases are inherited from the datasets used to train the models. Although
various methods have been proposed to mitigate these biases, systematic ways of integrating social bias tests
into development pipelines are still lacking. In this paper, we aim to evaluate the bias in ChatGPT, which is
based on the GPT-3 model, using Stereoset and comparing the model results with other transformer models like
gpt-2 and BERT. Stereoset is the most popular dataset currently available for benchmarking social biases. We
also aim to generate a preliminary dataset that takes into consideration the LGBTQ+ community while handling
gender bias.This dataset was motivated by WinoQueer which considers bias against all sexualities.
