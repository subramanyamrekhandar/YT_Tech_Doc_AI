
### Windows
Download the Windows installer from [Ollama.ai](https://ollama.ai/) and install.

## Usage
### Run a Default Model
```sh
ollama run llama2
```
This command will automatically download and run the model.

### List Available Models
```sh
ollama list
```
This shows all models available on your local machine.

### Pull a New Model
```sh
ollama pull mistral
```
This will download the `mistral` model for local use.

### Running a Custom Model
If you have a custom model file, you can load it using:
```sh
ollama run path/to/custom-model
```

## Managing Models
### Remove a Model
```sh
ollama rm <model-name>
```

### Update Ollama
```sh
ollama update
```

### Check Version
```sh
ollama --version
```

## Integrating Ollama into Python
You can interact with Ollama models in Python using the `subprocess` module or an API.

Example:
```python
import subprocess
result = subprocess.run(["ollama", "run", "llama2"], capture_output=True, text=True)
print(result.stdout)
```

For more details, visit [Ollama Documentation](https://ollama.ai/docs).

## Troubleshooting
- **Model not found?** Ensure the correct model name is used.
- **Installation issues?** Run the installer script again.
- **Performance slow?** Close unnecessary applications to free up RAM and CPU.

## Uninstall Ollama
To remove Ollama completely:
```sh
ollama uninstall
```
```

