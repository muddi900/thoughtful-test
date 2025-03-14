# Thoughtful AI Technical Trial

Thoughtful AI wants a submission of a technical test for their job application. This is my entry.

Check out the requirements [here](https://thoughtfulautomation.notion.site/AI-Technical-Screen-d4d381a8c38d40fc9287cdb6c4f9992a)

## Setup

Create a virtualenv. I am using Python3.12, so use that:

```bash
python3.12 -m venv venv
```

I am using Chainlit to build the UI and black for code formatting.


```bash
pip install chainlit black
```

or 

```bash
pip install -r requirements.txt
```

## Run

Running it is quite simple:

```bash
chainlit run main.py   
```

![image](screenshot.png)

It will only answer the hardcoded questions from the thoughtful AI dataset. You can check it out in [main.py](main.py)

