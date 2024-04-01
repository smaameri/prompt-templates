# PromptTemplates in LangChain

## Summary
Provided here is a bit of code to help get used to working with PromptTemplates in LangChain

I wrote an article which explores some of the concepts here, as well as walks through building each of the scripts.

## Getting started
Clone the repository, set up the virtual environment, and install the required packages

```
git clone 
cd prompt-templates
python3 -m venv .venv
. .venv/bin/activate
pip install -r requirements.txt
```

## Store your OpenAI API key
Copy the example env file

`cp .env.example .env`

Now copy your OpenAI API key into the `.env` file, and save the file. It should send up looking something like

`OPENAI_API_KEY=sk-`

## Run the script

```python
python3 prompt-templates.py
```