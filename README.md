An LLM(Large Language Model) application uing **Google gemini pro**( A powerful artificial intelligence (AI) model from Google that can understand text, images, videos, and audio. As a multimodal model, Gemini is described as capable of completing complex tasks in math, physics, and other areas, 
and understanding and generating high-quality code in various programming languages. **Gemini Pro** — our best model for scaling across a wide range of tasks. ) 
and 
**Langchain**( LangChain is an open source orchestration framework for the development of applications using large language models (LLMs). 
Available in both Python and Javascript-based libraries, LangChain’s tools and APIs simplify the process of building LLM-driven applications like chatbots and virtual agents. ) 
where we can multiple pdf documents with the help of **FAISS vector emebeddings**.

SIMPLE STEPS FOR ANY USER TO CREATE AND RUN THIS PROJECT-

  1.  Create a Project and open it with vs code directly or by locating it by cmd by typing: **code .** by command prompt through loaction pathway to open it in vs-code
  2.  create a virtual environment( name- venv ) by typing the folllowing command in the terminal of your vs-code: **conda create -p venv python==3.10 -y** ( since i'm using 3.10 also giving yes'y' to give permission to fulfill any requirement that occurs)
  3.  Activate your venv by typing: **conda activate venv/**
  4.  Then, install the requirements in the txt. file in your venv itself by typing: **pip install -r requirements.txt**
  5.  Run the app.py file by typing in terminal: **streamlit run app.py**
