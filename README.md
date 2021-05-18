# 36 Questions to Fall in Love With AI
This project asked the two conversational response generation models DialoGPT and BlenderBot the 36 questions to fall in love, as seen in the [New York Times](https://www.nytimes.com/2015/01/09/style/no-37-big-wedding-or-small.html) and originally developed as part of a psychological study conducted by [Aron et al. (1997)](https://journals.sagepub.com/doi/pdf/10.1177/0146167297234003).

## Table of Contents
1. [Installation](#installation)
2. [Project Motivation](#motivation)
4. [File Descriptions](#descriptions)
5. [Licensing, Authors, Acknowledgements](#licensing)

## Installation
The code requires Python versions of 3.* and general libraries available through the Anaconda package. In addition, the [transformers package](https://huggingface.co/transformers/index.html) by [Hugging Face](https://huggingface.co/) needs to be installed.

## Project Motivation <a name="motivation"></a>
I think the "36 questions to fall in love" are pretty well known by now and chances are that you, the reader, have already asked these questions another person. But what answers would you get if you asked an AI? I wanted to see how ridiculous the answers would be if I asked a chatbot. To my surprise, many answers made a lot of sense, were specific, and even displayed hints of empathy and personality. I wrote [a blog post](https://medium.com/@julia.nikulski/36-questions-to-fall-in-love-with-ai-89037cc040ab) about this on [my Medium](https://medium.com/@julia.nikulski). You can go there to get a nice overview of the best answers I received. I put some of them into nice photos in the article.

![Example of question-answer pair](https://github.com/julianikulski/ai-36-questions/blob/main/static/img/title_flowers_quote_layout.png)

## File Description <a name="descriptions"></a>
There is only one file of relevance, and that is the Jupyter Notebook `ai_36_questions.ipynb` I created on Google Colab. The code is relatively short and concise because I don't fine-tune the models but use them as is through the transformers library architecture.

## Licensing, Authors, Acknowledgements <a name="licensing"></a>
The code can be used under the [MIT License](https://opensource.org/licenses/MIT). So feel free to use the code or change it for your own project.

The data for the questions comes from http://36questionsinlove.com/. This is based on the questionnaire provided by the [New York Times](https://www.nytimes.com/2015/01/09/style/no-37-big-wedding-or-small.html) and originally by [Aron et al. (1997)](https://journals.sagepub.com/doi/pdf/10.1177/0146167297234003).
