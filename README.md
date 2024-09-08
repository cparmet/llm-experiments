This repo contains notebooks that explore LLMs and tooling, including <b>Llama 3</b> by Meta, <b>Gemma 2</b> by Google, <b>LangChain</b>, and <b>MLX</b>.  
  
To run:
1. Clone this repo locally
2. [Install poetry](https://python-poetry.org/docs/) on your machine if necessary
3. Navigate to the repo's root and run `poetry install`. This will create the virtual environment `llm-experiments` with the dependencies required by the notebooks.
4. Run the notebooks in your IDE, selecting the virtual environment `llm-experiments` 
5. To run the Agent code in `langchain.ipynb`, you'll need a serpapi API key stored in the environment variable `SERPAPI_API_KEY`. At the time of writing, you could get a free key for limited noncommercial use [here](https://serpapi.com/search).
  


<figure>
    <img src="img/llama.jpg" alt="Llama image" style="width: 100%;">
    <figcaption><small><i><a href="https://thesequence.substack.com/p/the-llama-effect-how-an-accidental">Image from The Sequence</i></small></figcaption>
</figure>