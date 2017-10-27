scipy-notebook with the following additions:
- Latex with all the extensions
- [nltk](http://www.nltk.org/) - Natural Language Toolkit for python
- [hmmlearn](https://github.com/hmmlearn/hmmlearn) - lib for unsupervised learning and inference of Hidden Markov Models

### After updating rebuild and push:

Run:

`docker build -t commandlinegirl/scipy-notebook .`

and

`docker push commandlinegirl/scipy-notebook`

### Running

`docker run -it -p 8888:8888 -v ~:/home/data commandlinegirl/scipy-notebook`
