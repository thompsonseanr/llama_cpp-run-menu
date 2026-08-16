# Llama.cpp Helper Scripts

> **Links:**  
> [llama.cpp](https://github.com/ggml-org/llama.cpp)  
> [Hugging Face](https://huggingface.co/)  
> [NVIDIA - Void Docs BTW](https://docs.voidlinux.org/config/graphical-session/graphics-drivers/nvidia.html)  

## Quickstart:

**IMPORTANT:** This assumes that you have llama.cpp installed and running on your machine as well as a Hugging Face account with pre-downloaded GGUF models. Distro is `Void`, yet these scripts **should** be fairly agnostic.

### Run the `llama.cpp-server` script:  

1) Make script executable for current user:  

Add to `~/.local/bin/`  

```
chmod +x llama.cpp-server
```

Restart terminal session by sourcing your $SHELL config (E.g.: `source ~/.zshrc` or `.bashrc`)  

2) Run and follow the prompts to start `llama-server`:  

```
llama.cpp-server
```

3) Go to: [http://127.0.0.1:8080](http://127.0.0.1:8080)  


### Run the `llama.cpp-cli` script  

1) Make script executable for current user:  

Add to `~/.local/bin/`  

```
chmod +x llama.cpp-cli
```

Restart terminal session by sourcing your $SHELL config (E.g.: `source ~/.zshrc` or `.bashrc`)  

2) Run and follow the prompts to start `llama.cpp-cli`:  

```
llama-cpp.cli
```

### Run the `llama.cpp-upgrade` script to pull and build the latest `llama.cpp` commit:  

**IMPORTANT:** This assumes that you have already built `llama.cpp` and have all of the build dependencies installed.  

1) Same steps for above scripts.

2) Run `llama.cpp-upgrade`:  

```
llama.cpp-upgrade
```