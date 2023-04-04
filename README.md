### Hi there 👋
🌱 I’m currently learning AI/ML, OpenAI API, and others.

My Programming languages
| Rank | Languages |
|-----:|-----------|
|     1| Python    |
|     2| Javascript|
|     3| SQL       |

<details>
<summary>My DevOps Tools</summary>

| Rank | Languages |
|-----:|-----------|
|     1| GitHub    |
|     2| Copilot   |
|     3| OpenAI    |
|     4| Docker    |

</details>

<details>
<summary>How to set up Python Development environment on Mac</summary>

 
Create python virtual environment with the same name of your github repo e.g. /Users/yourname/pyproject-web
  
-   `python3 -m venv ~/.pyproject-web`
-   `source ~/.pyproject-web/bin/activate`
-   `which python`    

 You should see something like this...
 
 /Users/yourname/.python-web/bin/python
 
Next, Make Some Basic Scaffolding

-   `touch Makefile`
 
 Add the below content to the Makefile
 ```
 install:
     pip install --upgrade pip &&\
         pip install -r requirements.txt
 
 test:
     python -m mytest --vv --cov=hello test_hello.py
 
 lint: 
     pylint --disable=R,C,E1120 hello.py
 
 format:
     black *.py
 
 all: install lint test
 
 ```
 
-   `touch requirements.txt`
 Add the below content to the Makefile
 ```
 click
 pylint
 pytest
 black
 ```` 
 
 
-   `touch hello.py && touch test_hello.py`    

 
</details>


<!--
**supiwmi/supiwmi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
