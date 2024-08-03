# rag-tutorial-v2

## Getting Started
Before running, ensure that ollama has been installed. If not, please install it [here](https://ollama.com/download). After that you **must** run `ollama serve`.

1. `python -m venv venv`
2. `source venv/bin/activate`
3. `pip install -r requirements.txt`
4. `python ./populate_database.py`
5. `python ./query_data.py "How much each players get for each round in Monopoly?"`

## Update document
1. Place the pdf file inside the `data`
2. `python ./populate_database.py`
