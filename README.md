# IT499
PDF Query AI Bot using Google Geminiand Streamlit

Codespace URL: https://special-guide-9g7555j94xqh9v9g.github.dev/

Make sure to use the terminal to run these commands to install the necessary packages:

1) pip install PyPDF2
2) pip install langchain
3) pip install langchain_google_genai
4) pip install -U langchain-community
5) pip install faiss-cpu

To run the application, type this command in the terminal: streamlit run app.py

Make sure you have your free Google Gemini api key. This program requires the user to enter their key at the very beginning.

You may get an Axios error when trying to process your pdf. If this occurs, relaunch the application and it should fix itself.

When using the RAG AI application, please ensure that your query matches the exact wording found in the document. If the query differs from the document's wording, the bot may not recognize or accurately process the question.
