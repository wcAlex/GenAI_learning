
In this repository, we captured the examples of different strategies of prompt engineering. 

Most of the code/notebooks are from the course "[ChatGPT Prompt Engineering for Developers](https://learn.deeplearning.ai/chatgpt-prompt-eng/lesson/1/introduction)"

## setup 
https://pypi.org/project/openai/

```
conda update conda
conda create -n llm_dev python=3.10 anaconda
conda activate llm_dev

pip install --upgrade openai
pip install python-dotenv
pip install langchain

```

Create open api keys at: https://platform.openai.com/account/api-keys

## run the notbooks
```
cd {work_folder}
jupyter lab --notebook-dir .

```
