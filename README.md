# Textfile-Q-N-A-Gradio-Huggingface

### STEPS:
## How to run? 
### STEP 01- Create a conda environment after opening the repository
```bash
conda create -p textfileqnavenv python -y
```

```bash
source activate ./textfileqnavenv
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

### STEP 03- run application
```bash
Python app.py
```

##### after download move the model to code folder
```bash 
sudo mv ./models--deepset--roberta-base-squad2/ /Users/mayankchugh/gitRepos/mayankchugh.learning/Textfile-Q-N-A-Gradio-Huggingface/Model/models--deepset--roberta-base-squad2
```

```bash
./Model/models--deepset--roberta-base-squad2/snapshots/cbf50ba81465d4d8676b8bab348e31835147541b
```

## Prompt
```bash
write a python script that would take a file object as input and return the content of the files as output.
```

```bash
write a small story about friendship between a machine and a boy.
```

##### after download move the model to code folder
```
cd /Users/mayankchugh/.cache/huggingface/hub/
```

[Gradio documentation link](https://www.gradio.app/docs/gradio/file)

### related to question

[Wikipedia Link](https://en.wikipedia.org/wiki/Continent)
