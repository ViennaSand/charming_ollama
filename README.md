# charming_ollama
Coupling ollama with the charming llm scripts 

For this to work you need to install ollama first and download the model you want to use.
Here I use mistral-nemo 

## To check what models you already have as models:
### Type in terminal:
ollama list
### Then to remove the old ones (if any):
ollama rm the_old_model
### To install the new one:
ollama pull mistral-nemo 

Now, it is usable from your python script
