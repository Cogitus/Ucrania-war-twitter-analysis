# Ucrania-war-twitter-analysis

This project aims to analyse, by using the twitter API and some network analysis techniques, how the people is reacting to the possibility of a war between Russia and USA/Ukraine.

## What is the problem?

The problem is that the people of Ukraine are not aware of the possibility of a war between Russia and USA. The people of Ukraine are not aware of the possibility of a war between Russia and USA.

## Built with

- [Python](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [Twitter API](https://developer.twitter.com/en/docs/tweets/search/api-reference/get-search-tweets)
- [NetworkX](https://networkx.github.io/)
- [Pandas](https://pandas.pydata.org/)
- [Twython](https://twython.readthedocs.io/en/latest/)

## Gettin' started

First of all make sure you have an twitter API account configured. Then you need to have Python and pip installed. The next step is to install the required packages.

If you want to built a conda environment for this project, you can use the following command:

```bash
$ conda create --file environment.yml
```

Then you can activate the environment with:

```bash
$ conda activate ucrania-war-twitter-analysis
``` 

Twython is a Python library that allows you to access the Twitter API.

```bash
$ pip install Twython
```

NetworkX is a Python library that allows you to create graphs.

```bash
$ pip install networkx
```

Pandas is a Python library that allows you to create dataframes.

```bash
$ pip install pandas
```

## Run the notebook

```bash
$ python Twitter.ipynb
```
