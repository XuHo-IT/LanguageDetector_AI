# LanguageDetector-AI 🧠🌐

A lightweight AI-powered language detection web app powered by .NET 9 and [Ollama](https://ollama.com), utilizing the `gemma3` model for natural language processing.
This AI will help you in terms of learning english

---

## 🚀 Features
- Detect the language of user input using a local LLM.
- Uses Ollama with the `gemma3` model.
- Built with ASP.NET Core (.NET 9).
- Easily extensible for more NLP features.

---

## 📦 Prerequisites

- [.NET 9 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/9.0) (or compatible version)
- [Ollama](https://ollama.com) (for running local language models)
- `gemma3` model for Ollama
- Git *(optional, for version control)*

---

## 🛠 Installation

```bash
# Clone the repository (change the URL if yours is different)
git clone https://github.com/your-username/LanguageDetector-AI.git && \
cd LanguageDetector-AI && \

# Pull the gemma3 model using Ollama
ollama pull gemma3 && \

# Restore and build the .NET project
dotnet restore && \
dotnet build && \

# Run the application
dotnet run

