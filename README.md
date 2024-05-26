# Medical_Chatbot_Using_Llama2
This version of Medical Chatbot utilizes use of [FAISS](https://github.com/facebookresearch/faiss) library by Meta for vector storage and uses Meta's LLM [LLAMA-2](https://llama.meta.com/llama2/).

## Create a virtual env (ubuntu)
``` bash
python3 -m venv env
```

## Activate the env
``` bash
source env/bin/activate
```

## Install dependencies

```bash
pip install -r requirements.txt
```

## Install the model

Can download the model from [here](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main)

## Run the app

```bash
python app.py
```
