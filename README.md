# LLM testing for cmpe 187

## prereqs
- add `.env` file with following api keys:
    - `OPENAI_API_KEY=`
    - `GEMINI_API_KEY=`
- DeepSeek is run locally using [LM Studio](https://lmstudio.ai/)
- create venv with `python3 -m venv venv`
    - project was made with `python 3.12.8`, use this version or higher when making venv
- activate venv (`source venv/bin/activate`) and install requirements with `pip install -r requirements.txt`

## running
- activate venv with `source venv/bin/activate`
- run `jupyter notebook` and visit a notebook to run it in a browser