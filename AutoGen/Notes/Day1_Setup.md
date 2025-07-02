# Steps to Setup

### Installation of Python
**Make Sure to Install Python 3.10 or above (Autogen works with >3.10 version of python)**

1. Go to [python.org](https://www.python.org/downloads/) and download Python >= 3.10.
2. While setting up make sure to add python to path.
3. Verify by opening command prompt and type `python` or `python -V`

### Installing VS Code

1. Go to [official website](https://code.visualstudio.com/download)
2. Download which suits your os(Mac/Linux/Windows).
3. After setting up install python and jupyter extensions from VS Code

### Installing AutoGen

1. Follow this [steps](https://microsoft.github.io/autogen/stable/user-guide/agentchat-user-guide/installation.html)
2. Open your Visual Studio Code and Open your project folder
2. In your project folder open terminal.
    * Look out for `Terminal` in the menu and click on it
    * Choose `New Terminal`
    * In terminal type `python -m venv <name-of-your-env>`
    * activate it by typing `<name-of-your-env>\Scripts\activate`
3. Now in same terminal type `pip install autogen-agentchat` or `python install -U "autogen-agentchat"`
4. Save your installed libraries using `pip freeze > requirements.txt`
5. Install OpenAI for Model Client by typing `pip install "autogen-ext[openai]"`