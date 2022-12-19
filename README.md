# resume_recommender
Using Retrieve-and-Rank to recommend resumes

Transformer models often have a [maximum sequence length](https://huggingface.co/course/chapter2/5?fw=tf#longer-sequences) of 256 or 512 tokens.  This repo is an experiment in how to tokenize longer inputs - I normally just [split on whitespace](https://docs.python.org/3/library/re.html#re.split), but I wanted to try [NLTK's sent_tokenize](https://www.nltk.org/api/nltk.tokenize.html) function.

### References
Jiechieu, K.F.F., Tsopze, N. Skills prediction based on multi-label resume classification using CNN with model predictions explanation. Neural Comput & Applic (2020). https://doi.org/10.1007/s00521-020-05302-x
