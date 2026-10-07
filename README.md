# mini-rag

This is a minimal implementation of the RAG model for question answering.

## Requirments

-python 3.8 or later

### install python using Miniconda

1- Download and install Miniconda from here (https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh)
2- Create a new environment using the following command:
```bash
$ conda create -n mini-rag python=3.8
```
3- Activate the environment 
```bash
$ conda activate mini-rag
```
### (optional) Setup yuor command line interface for better readability

```bash
export PS1="\[\033[01;32m\]\u@\h:\w\n\[\033[00m\]\$ "
```
### Installation

### Install the required packages

```bash
$ pip install -r requirements.txt
```

### Setup the environment variables

```bash
$ cp .env.example .env
```

Set your environment variables in the `.env` file. Like `OPENAI_API_KEY` value.