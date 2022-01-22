# Assignment 3

This assignment is aimed to prepare you for your final projects. The goal is to learn about different tasks that are currently studied in NLP. We will start by looking at task types that are provided by the `pipelines` module of the of the `transformers` library. These define types for input and output for Neural Models. For example, a  `TextClassificationPipeline` takes a sequence of text and outputs a class, much like our `NaiveBayes` classifier. A `QuestionAnsweringPipeline` requires a `context` and a `question` about the `context` and returns the portion of the `context` that contains the answer.

The pipelines describe broad task types, but there are more specific downstream tasks. For example, Sentiment Analysis and Spam Detection are both examples of Text Classification. Models are trained and _fine-tuned_ to perform well on the individual tasks. The recent explosion in large language models to produce *contextual embeddings* means that many of these tasks are performed using a general purpose base language model and a _head_ layer. The general purpose model is often _fine-tuned_ on the individual task to produce better results. The specifics vary from task to task. These models, fine-tuned or specially trained, are made available through [huggingface.io’s](https://huggingface.io) Model Hub. Downloading and running them is reduced to a few lines of code.

## Your assignment

For your final project, you will do a deep dive into a task. You will write a literature review and try to apply your own modifications. To get you started, your current assignment is to choose a downstream task and describe the problem. This will require extensive googling and reading.
- ⭐️ What is the task description? 
	- What are the inputs and outputs?
	- What metrics are used to measure performance on the task?
- ⭐️ What models are commonly used for this task?
- ⭐️ ⭐️ What training and testing datasets are available for your task?
	- How do these datasets differ?
	- What are some concerns or considerations regarding these datasets? (remember _Model Cards_)
- ⭐️ ⭐️ ⭐️ How do different models perform on different datasets?
	- Use online tutorials and the `transformers` library to run tests in colab.
	- Report the appropriate metrics for some combination of models and datasets. You don’t have to do every combination, but you should do at least 10 combinations. Present the results in a table.
	- Do the descriptions of the tasks or models provide any potential insights into their performance?
- ⭐️ Find some academic papers that discuss your task

## Expectations
I expect everything to be written in your own words. Each major bullet point is worth at least 200 words.
Your report should be written into a colab notebook. Try to include enough detail so that your classmates can understand without referencing outside material and try out the demos themselves.

## ⭐️ ⭐️ In class presentation (5-10 min)
On _Wednesday_, you will present a basic description of the task you are working on and what the input and outputs look like.

# BEFORE YOU START WORKING ON YOUR ASSIGNMENT
Post the task you intend to pursue in Slack. I will make a channel specifically for this. I want no more than two people working on each subtask. You may choose to work in pairs, in which case I will naturally expect more thoroughness.
