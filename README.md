# Regulation Q&A Demo

An exercise to demonstrate retrieval augmented generation (RAG).

Task: Answer whether a permit is needed, and what are the conditions, for the use and development on land (e.g. building a car park or swimming pool in a residential property)  
Data: A very small sample of regulations from Section 32.03 of [Yarra Ranges Planning Scheme](https://planning-schemes.app.planning.vic.gov.au/Yarra%20Ranges/ordinance?f.Scheme%7CplanningSchemeName=)

## Setup

Run the go script to install pre-requisite dependencies. The go script will install Python 3 and Poetry, and create a virtual environment on the host. 

```shell script
# mac users
scripts/go/go-mac.sh
```

Configure your IDE to use the python virtual environment created in the go script. 
- [PyCharm instructions](https://www.jetbrains.com/help/pycharm/creating-virtual-environment.html#existing-environment)
- [VS Code instructions](https://code.visualstudio.com/docs/python/environments)

## Tasks that you can run

```shell script
# Activate virtual environment
poetry shell

# Set OPENAI API key (https://platform.openai.com/docs/introduction)
export OPENAI_API_KEY='your key'

# Start jupyter notebook
jupyter notebook
```
