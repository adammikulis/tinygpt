This is a repository for training a small GPT2-based model locally. It utilizes the distilgpt2 model from HuggingFace: https://huggingface.co/distilgpt2

The source text is Grimm's Fairy Tales, chosen due to its status as public domain and common familiarity with its stories: https://www.gutenberg.org/files/2591/2591-h/2591-h.htm

Run within the project folder to install dependencies in your Python environment:

pip install -r requirements.txt

Execute the code in each cell of main.ipynb to train a GPT model on your CPU or GPU (Nvidia), then load it and test it with your prompts. Training requires 12GB of RAM/VRAM.
