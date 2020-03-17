# nlp-in-python
Welcome to the Natural Language Processing in Python Tutorial!

We will be going through several Jupyter Notebooks during the tutorial and use a number of data science libraries along the way. The easiest way to get started is to download Anaconda, which is free and open source. When you download this, it comes with the Jupyter Notebook IDE and many popular data science libraries, so you don’t have to install them one by one.

Here are the steps you’ll need to take before the start of the tutorial:
1. Download Anaconda

I highly recommend that you download the Python 3.7 version.
2. Download the Jupyter Notebooks

Clone or download this Github repository, so you have access to all the Jupyter Notebooks (.ipynb extension) in the tutorial. Note the green button on the right side of the screen that says Clone or download. If you know how to use Github, go ahead and clone the repo. If you don't know how to use Github, you can also just download the zip file and unzip it on your laptop.
3. Launch Anaconda and Open a Jupyter Notebook

Windows: Open the Anaconda Navigator program. You should see the Jupyter Notebook logo. Below the logo, click Launch. A browser window should open up. In the browser window, navigate to the location of the saved Jupyter Notebook files and open 0-Hello-World.ipynb. Follow the instructions in the notebook.

Mac/Linux: Open a terminal. Type jupyter notebook. A browser should open up. In the browser window, navigate to the location of the saved Jupyter Notebook files and open 0-Hello-World.ipynb. Follow the instructions in the notebook.
4. Install a Few Additional Packages

There are a few additional packages we'll be using during the tutorial that are not included when you download Anaconda - wordcloud, textblob and gensim.

Windows: Open the Anaconda Prompt program. You should see a black window pop up. Type conda install -c conda-forge wordcloud to download wordcloud. You will be asked whether you want to proceed or not. Type y for yes. Once that is done, type conda install -c conda-forge textblob to download textblob and y to proceed, and type conda install -c conda-forge gensim to download gensim and y to proceed.

Mac/Linux: Your terminal should already be open. Type command-t to open a new tab. Type conda install -c conda-forge wordcloud to download wordcloud. You will be asked whether you want to proceed or not. Type y for yes. Once that is done, type conda install -c conda-forge textblob to download textblob and y to proceed, and type conda install -c conda-forge gensim to download gensim and y to proceed.



# WORD2VEC Model a beginner approach

##Why is Natural Language Processing difficult?
 
Computers interact with Human through structured , clear , unambigous programming languages. Normally Natural Languages are unambigious as it is 100% dependent on the context in the word is mentioned.Words behave differently when used as noun or verb.There lies the relevance of NLP in the field of AI.This is what makes this field interesting and difficut in the field of AI.

##What can be accomplished from NLP?
Several tasks can be accomplished by enabling computers to “understand” human language. One live example is this software that I am using to check spellings and grammar in this article. Here are some tasks which are being done presently using NLP:
    1. Spelling and grammar check
    2. Finding synonyms and antonyms
    3. Parsing information from documents, websites
    4. Understanding meanings of sentences, documents and queries
    5. Machine Translation (e.g Translate text from English to German)
    6. Question Answering and doing tasks (e.g scheduling appointments etc.)
    
    
  ##Representing text in natural language processing
  How can we change the world of words into some representations which algorithms can understand. 
  
