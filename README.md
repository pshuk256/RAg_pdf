# rag-tutorial-v2

## Running with OLLAMA

1. Install the following packages:
```shell
$ pip3 install langchain
$ pip3 install chromadb
$ pip3 install pypdf
$ pip3 install pytest
$ pip3 install langchain-community
$ pip3 install -U langchain-chroma
```

2. Make sure you have ollama on your machine by checking out the instructions in [Ollama Github](https://github.com/ollama/ollama)

3. Once ollama has been downloaded, start the server in another terminal window:
```shell
$ ollama serve
```

4. Pull the models needed:
```shell
$ ollama pull nomic-embed-text
$ ollama pull mistral
```

5. Run the program. Below is an example:
```shell
$ python3 query_data.py "how much total money does a player start with in Monopoly?"
```

The return answer should be shown in the terminal.


