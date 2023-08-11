<h1 align="center"><b>TerminalGPT</b></h1>
<h4 align="center">A terminal application built using ChatGPT for prompting ChatGpt from your terminal.</h4>

<p align="center">
    <img src="" alt="Project Banner" width=60% height=60%/>
</p>

## Table of Contents

- [Introduction](#introduction)
- [Technical Requirements](#technical-requirements)
- [Project Structure](#project-structure)
- [Key Functionalities](#key-functionalities)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)

## Introduction

TerminalGPT is a CLI based application which allows you to use pre-scripted prompts, as well as general prompts.

## Technical Requirements

To run TerminalGPT:

- Python 3.7 or later
- OpenAI API key

## Project Directory Hierarchy

Upon successful setup (see **Getting Started**), you should see the following project directory hierarchy.

```
├── app.py
├── Pipfile
├── Pipfile.lock
└── README.md
```

- `app.py`: Main application file used to run the application in your terminal.
- `Pipfile` and `Pipfile.lock`: Files specifying project dependencies when using `pipenv`.
- `README.md`: Project documentation providing an overview, setup instructions, and other details.

## Key Functionalities

1. Play a choose your own adventure game with ChatGPT as your host.
2. Translate any phrase into any language, along with a short lesson on how and why it is spoken.
3. Generate a chord progression with a given emotional quality.
4. Get a short lesson on any topic in a coding language of your choice.
5. Give TerminalGPT a general prompt

## Getting Started

1. Clone this repository to your local machine:

```bash
git clone git@github.com:avbbarker/TerminalGPT.git
```

2. Navigate to the project directory:

```bash
cd TerminalGPT
```

3. Install the required dependencies using pipenv:

```bash
pipenv install
```

4. Run the TerminalGPT app:

```bash
pipenv run python app.py
```

5. Navigate to https://platform.openai.com/account/api-keys and download generate an API key.
   > app.py, replace "OPENAI_API_KEY" in openai.api_key = OPENAI_API_KEY on line 4 with the API key you generated from https://platform.openai.com/account/api-keys

```py
4   openai.api_key = "your_api_key_goes_here"
```

## Dependencies

The NFL Player Statistics Dashboard relies on the following libraries:

- OpenAI: An API for pinging ChatGPT and recieving responses from it.
