### 🚀 Starting setup:

In your terminal, navigate to the project repository. Then let's create an isolated Python environment which will contain dependencies **unique** to this project:
```python
python3 -m venv env
source env/bin/activate
```

Install dependencies:

```python
pip install --upgrade pip
pip install -r requirements.txt
```

### 🚀 Project structure:

    streamlit-llm
    ├── .streamlit
    │   └── config.toml
    ├── app                   
    │   ├── main.py            
    │   ├── utils.py              
    │   └── ...                 
    ├── assets
    │   ├── x.png                         
    │   └── z.png  
    ├── data
    ├── env
    └── requirements.txt


