## This Project is RAG Based Application called Document Portal
## Features:
```
1. Analysing Documents
2. Compare Documents
3. Talk with single Doc
4. Talk with multiple different doc
```

## Requirements
### LLM Models
- **Groq** (Free)
- **OpenAI** (Paid)
- **Gemini** (15 Days Free Access)
- **Claude** (Paid)
- **Hugging Face** (Free)
- **Ollama** (Local Setup)

### Embedding Models
- **OpenAI**
- **Hugging Face**
- **Gemini**

### Vector Databases
- **In-Memory**
- **On-Disk**
- **Cloud-Based**

## API Keys

### GROQ API Key
- [Get your API Key](https://console.groq.com/keys)  
- [Groq Documentation](https://console.groq.com/docs/overview)

### Gemini API Key
- [Get your API Key](https://aistudio.google.com/apikey)  
- [Gemini Documentation](https://ai.google.dev/gemini-api/docs/models)

## Commands we need to follow to Set up the Project

## below command is for windows(CMD)

```
mkdir <project_folder_name>
```

```
cd <project_folder_name>
```

```
code .
```

## for conda env setup

```
conda create -p <env_name> python=3.10 -y
```

```
conda activate <path_of_the_env>
```

```
pip install -r requirements.txt
```

## git commands(this commands is for the later uses)

```
git init
```

```
git add .
```

```
git commit -m "<write your commit message>"
```

```
git push
```
## set env variable to set llm model
```
example: set LLM_PROVIDER = google
Before this set this as env variable. There are various ways to do it, do it according to your wish , i have set it in my env file of my venv.
```
