# Langchain Crash Course

This is based on a [YouTube Video](https://www.youtube.com/watch?v=MlK6SIjcjE8) from Nick Renotte.AttributeError

Starting source code from his linked repository https://github.com/nicknochnack/Langchain-Crash-Course/

> **NOTE**
> This code works but is incomplete as it does not track tokens and generate a complete script, nor does it store vectors.


# Environment Setup
## Python Environment
Activate your Python virtual environment, if using it
### Windows
```
\.venv\Scripts\Activate.ps1
```
### MacOS or Linux
```
./.venv/Scripts/activate
```

## Install Dependencies
```
pip install python-dotenv streamlit langchain openai wikipedia tiktoken
```

# Launch App
```
cd Apps/Generative/Langchain-Crash-Course
streamlit run app.py
```
A browser window will open, the app is running there.

# Reload App
There is a hamburger menu icon ☰ in the upper right of the app window, and on that menu is `Rerun`.

# Kill App
On the command line, `Control-C`.