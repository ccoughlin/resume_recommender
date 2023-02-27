# resume_recommender
Experiments in using NLP to recommend resumes

## Resume Recommender
[direct link to notebook](https://github.com/ccoughlin/resume_recommender/blob/main/Resume%20Recommender.ipynb)

Using Retrieve-and-Rank to recommend resumes

Transformer models often have a [maximum sequence length](https://huggingface.co/course/chapter2/5?fw=tf#longer-sequences) of 256 or 512 tokens.  This repo is an experiment in how to tokenize longer inputs - I normally just [split on whitespace](https://docs.python.org/3/library/re.html#re.split), but I wanted to try [NLTK's sent_tokenize](https://www.nltk.org/api/nltk.tokenize.html) function.

### References
Jiechieu, K.F.F., Tsopze, N. Skills prediction based on multi-label resume classification using CNN with model predictions explanation. Neural Comput & Applic (2020). https://doi.org/10.1007/s00521-020-05302-x

## Resume Builder
[direct link to notebook](https://github.com/ccoughlin/resume_recommender/blob/main/Resume%20Builder.ipynb)

You're supposed to tailor your resume to each job ["to showcase your most relevant qualifications"](https://www.indeed.com/career-advice/resumes-cover-letters/tailoring-resume). I've often wondered if this could be automated, and wanted to work through an implementation idea with OpenAI.
