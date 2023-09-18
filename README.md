# AI_Applications
The repository contains code for AI applications that I am trying to ideate on using techniques likes RAG etc. 

Chatting with datafiles
1. Upload a document(csv/xlsx) for now and start asking questions.
2. This is currently added as a streamlit application in ask_excel.py


1. Create a python env and install the required libraries using
```
pip install -r requirements.txt
```
3. Set up your openai key part as env variable using the command:

```
conda env config vars set OPENAI_API_KEY = (add key here)
```

5. Launch app using:
```
streamlit run ask_excel.py
```

Roadmap:

1. Currently simple qustions are answered accurately. The next step is to add logic for reasoning to ensure the model is able to answer difficult queries. 
2. Run using a local LLM
3. Database integrations.




