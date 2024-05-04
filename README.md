# MultiPDFchatMistral-7B

## Source

https://www.youtube.com/watch?v=tqpXvPzteT4
https://github.com/InsightEdge01/MultiPDFchatMistral-7B


## Mistral 7B LLM

Mistral 7B is a 7-billion-parameter language model released by Mistral AI

https://github.com/mistralai/mistral-src

https://huggingface.co/TheBloke/Mistral-7B-Instruct-v0.1-GGUF


Download model file.

```shell
pip3 install huggingface-hub
huggingface-cli download TheBloke/Mistral-7B-Instruct-v0.1-GGUF mistral-7b-instruct-v0.1.Q4_K_M.gguf --local-dir . --local-dir-use-symlinks False
```


```shell
curl -L https://huggingface.co/TheBloke/Mistral-7B-Instruct-v0.1-GGUF/resolve/main/mistral-7b-instruct-v0.1.Q4_K_M.gguf\?download\=true -o mistral-7b-instruct-v0.1.Q4_K_M.gguf
```

## Run

```shell
streamlit run --server.port 9999 main.py
```

## Usage of GPU

CMAKE_ARGS="-DLLAMA_CUBLAS=on" pip install llama-cpp-python --force-reinstall --upgrade --no-cache-dir


## Stuff

```shell
nvcc --version
```

## Links
https://www.youtube.com/watch?v=0XDLyY90E2c
