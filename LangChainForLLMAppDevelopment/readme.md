Course: LangChain for LLM Application Development - https://learn.deeplearning.ai/langchain/lesson/1/introduction

Most of the content are from the course "[ChatGPT Prompt Engineering for Developers](https://learn.deeplearning.ai/chatgpt-prompt-eng/lesson/1/introduction)", for the notebook files, I modify them on top of https://github.com/ArslanKAS/LangChain-for-LLM-App-Development. 

## setup 
https://pypi.org/project/openai/

```
conda update conda
conda create -n llm_dev python=3.10 anaconda
conda activate llm_dev

pip install --upgrade openai
pip install python-dotenv
pip install --upgrade langchain

```

Create open api keys at: https://platform.openai.com/account/api-keys

Create a .env file and set
OPENAI_API_KEY={api key}

## run the notbooks
```
cd {work_folder}
jupyter lab --notebook-dir .

```
