# Hugging Face Transformers

This part of assignment is about leveraging the Hugging Face Transformers library for a variety of tasks including text classification, named entity recognition, question answering, text summarization, translation, zero-shot classification, computer vision, audio analysis, and table question answering. This assignment provided an overview of how Transformer models can be applied to solve diverse problems in natural language processing (NLP), computer vision, and audio processing.

## Introduction

Transformer models have revolutionized the field of machine learning, particularly in NLP. The Hugging Face Transformers library offers an extensive collection of pre-trained models that can be easily used for a wide range of tasks. This section aims to explore the capabilities of these models, showcasing their application in different domains.

## Text Classification
Text classification involves categorizing text into predefined categories. Transformer models excel in this task by understanding the context and nuances of the text, leading to highly accurate classifications making them highly effective for sentiment analysis, topic categorization, and more. Here I have used the movie wikipedia dataset.

## Named Entity Recognition (NER)
NER is a task where the model identifies and classifies key information (entities) in the text into predefined categories such as the names of persons, organizations, locations, expressions of times, quantities, monetary values, percentages, etc. Transformers can effectively recognize these entities within a larger corpus. Here I have used the movie wikipedia dataset.

## Text Summarization
Text summarization aims to shorten a text document, creating a summary that retains the most important points of the original text. Transformer models can generate coherent, concise, and relevant summaries regardless of the text's complexity. Here I have used the movie wikipedia dataset and summarizing the plot. 

## Question Answering
Question Answering model demonstrate an understanding of context within a body of text, providing accurate answers to queries. Their ability to digest, interpret, and retrieve specific information from text is unparalleled. Here I am using a context on the "ISRO" and answering some questions based on the context. 

## Translation
Translation models convert text from one language to another. With the advent of Transformer models, machine translation has seen significant improvements in accuracy and fluency, making it possible to translate complex texts with subtleties preserved showcasing fluency and accuracy. Here I am using the 'Helsinki-NLP/opus-mt-en' model to translate text in different languages.

## Zero-shot Classification
Zero-shot classification models can classify text into categories that they have not seen during training. This is particularly useful for classifying text into a large number of categories or when training data is scarce, demonstrating model adaptability and inference capabilities. Here I am using 'facebook/bart-large-mnli' model to perform some predictions on a context.

## Computer Vision: Analyzing Images

Transformer models are not limited to NLP tasks. They have also been adapted for computer vision tasks, showing remarkable performance in object detection, image classification, and semantic segmentation, interpreting visual data with high accuracy. Here I am using 'microsoft/beit-base-patch16-224' model with 'fiftyone' to predict.

## Audio: Processing Sound

In the domain of audio processing, Transformer models can perform tasks such as speech recognition, sound classification, and audio source separation. These models can effectively handle the temporal nature of audio data, showcasing their versatility with audio data. Here I am using the 'speechbrain' and generated some voice samples.

## Table Question Answering

Table Question Answering models represent another facet of transformers' capabilities, enabling the analysis and interpretation of tabular data to answer complex queries, illustrating the models' adaptability to structured data formats. I have used a synthetic data on Fictional football league and answered some questions.
