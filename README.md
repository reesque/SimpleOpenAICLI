<h1 align="center"><b>Simple OpenAI Command-Line Interface</b></h1>
<h4 align="center">Wrapper for OpenAI API, allows you to prompt from your terminal</h4>

```
Usage: openaicli command [ARGUMENTS]...
Available commands:
	models					Show all available models to use from
	prompt <MODEL_NAME> <TEXT_PROMPT>	send a text prompt to OpenAI API, expects a text response
```

# Requriement
- An OpenAI API key. This should be stored in this root within file named `api_key.txt`

# Installation
- Run `pip install -r requirements.txt`

# Usage
- For Linux and MacOS, execute `./openaicli ...`
- For Windows, it is required to run `python .\openaicli ...` 
