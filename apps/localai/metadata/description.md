# LocalAI - Your Local AI Model Server

LocalAI is a free, Open Source alternative to OpenAI's API. It acts as a drop-in replacement REST API that's compatible with OpenAI API specifications for local AI inferencing. Run LLMs, generate images, audio, and more locally with consumer-grade hardware.

## Features

- 📖 Text generation with GPTs (llama.cpp, transformers, vllm)
- 🗣 Text to Audio generation
- 🔈 Audio to Text (whisper.cpp)
- 🎨 Image generation
- 🔥 OpenAI-compatible API
- 🧠 Embeddings generation
- 🖼️ Direct Huggingface model downloads
- 🥽 Vision API support
- 📈 Reranker API
- 🆕 P2P Inferencing
- 🔊 Voice activity detection
- 🌍 Integrated WebUI

## Configuration

### Basic Settings
- **Default Model**: Model to load on startup (e.g., phi-2, llama-3.2-1b-instruct:q4_k_m)
- **Debug Mode**: Enable detailed logging
- **GPU Support**: Enable NVIDIA GPU acceleration
- **Context Size**: Maximum context size for model inference

### Model Management
Models are stored in the `models` directory and can be loaded in several ways:
- From the model gallery
- Directly from Huggingface
- From the Ollama registry
- Using configuration files
- From standard OCI registries

### GPU Support
When enabling GPU support, make sure your system has:
- NVIDIA GPU with CUDA support
- Proper NVIDIA drivers installed
- Docker GPU runtime configured

## Getting Started

1. Install through RunTipi
2. Configure basic settings
3. Access the WebUI or API endpoints
4. Load models using the LocalAI CLI or WebUI:
   ```bash
   local-ai models list              # List available models
   local-ai run llama-2-7b:q4_k_m   # Run specific model
   ```

## Important Notes

- Model files can be large, ensure sufficient storage
- GPU support requires proper NVIDIA setup
- Initial model download may take time
- API is compatible with OpenAI clients

For more information, visit [LocalAI Documentation](https://localai.io/).