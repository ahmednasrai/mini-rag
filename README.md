# mini-rag-app

This is minimal implementation of the RAG model for question answering


## Requirements

- Python 3.8 or later

#### Install Python using MiniConda

1) Download and install MiniConda from [here](

)
2) Create a new enviroment using the following command:
'''bash
$ conda create -n mini-rag python=3.8
'''
3) Activate the enviroment :
'''bash
$ conda activate mini-rag
'''

 ## Installition

 ### Install the required package

 '''bash
 $ pip install the required packages

 '''

### Setup the environment Variables

'''bash

$ cp .env.example .env
'''

Set your environment variables in the '.env' file like 'OPENAI_API_KEY' value .

## Run the fastapi server

''' bash
uvicorn main:app --reload --host 0.0.0.0 --port 5000
'''



