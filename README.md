# Llama.cpp Run Menu

> **Links:**  
> [llama.cpp](https://github.com/ggml-org/llama.cpp)  
> [Hugging Face](https://huggingface.co/)  
> [NVIDIA - Void Docs BTW](https://docs.voidlinux.org/config/graphical-session/graphics-drivers/nvidia.html)  

## Quickstart:

**IMPORTANT:** This assumes that you have llama.cpp installed and running on your machine as well as a Hugging Face account with pre-downloaded GGUF models.  

### Run the `llama.cpp-run` script  

1) Make script executable for current user:  

Add to `~/.local/bin/`  

```
chmod +x llama.cpp-run
```

Restart terminal session by sourcing your $SHELL config (E.g.: `source ~/.zshrc` or `.bashrc`)  

2) Run and follow the prompts to start `llama-cli`:  

```
llama-cpp.run
```
