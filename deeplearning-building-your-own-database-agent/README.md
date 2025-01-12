# Building Your Own Database Agent

https://learn.deeplearning.ai/courses/building-your-own-database-agent/



### Install Python using pyenv

https://realpython.com/intro-to-pyenv/


### Create a Virtual Environment

`pyenv virtualenv 3.13.1 scripts`


### Install requirements

`pip3 install -r requirements.txt`


### Setup database

1. Install SQLite3
2. `mkdir db && cd db && sqlite3 test.db` 


### Run script

```
export OPENAI_API_KEY="<openai-key>" 
python database_agent.py
```