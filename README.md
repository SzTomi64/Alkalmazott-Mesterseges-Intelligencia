# Alkalmazott-Mesterseges-Intelligencia

In this project I attempt to create an LLM model that optimizes python code.

The model takes small code snipets (3-4 lines of code) with a small description of what the code is doing as input, and returns a (hopefully) more optimal version of the code and optionally also what methodes it uses to achive this goal.

In the data.csv file, we find 109 unoptimized-optimized code pairs generated with ChatGPT.

In the code optimizer notebook, we can find the training algorithm. I used a Llama 3.2 model and finetuned it on my custom dataset.

In the code_test notebook we can find some of the question-answer pairs tested with a timer.

The training requiers access to the Llama model and wandb authetication.
