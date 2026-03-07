# Prerequisites Setup for Rasa Chatbot Project

## Overview

Before starting the development of the Rasa chatbot project, several prerequisites were installed and configured to ensure a proper development environment.

## 1. Python Installation

Python version **3.10.x** was installed because Rasa supports Python versions 3.8–3.10.

Command used to verify installation:

```
python --version
```

Output:

```
Python 3.10.x
```

## 2. Python Virtual Environment

A virtual environment was created to isolate project dependencies.

Command used:

```
python -m venv rasa_env
```

To activate the virtual environment:

Windows:

```
rasa_env\Scripts\activate
```

After activation the terminal shows:

```
(rasa_env)
```

## 3. Rasa Installation

Rasa framework was installed using pip.

Command used:

```
pip install rasa
```

Verification command:

```
rasa --version
```

## 4. Development Environment

The project was developed using **Visual Studio Code (VS Code)** as the IDE.

Extensions used:

* Python Extension
* YAML Support

## 5. Rasa Project Initialization

A new Rasa project was created using the following command:

```
rasa init
```

This generated the default project structure including:

* data/
* config.yml
* domain.yml
* actions/
* endpoints.yml

## 6. Training Data Format

Rasa uses **YAML format** for defining intents and examples.

Example training data snippet:

```
version: "3.1"

nlu:
- intent: greet
  examples: |
    - hello
    - hi
    - hey
```

## 7. Required Libraries

The following libraries were installed:

* rasa
* pip
* python

## Conclusion

All prerequisites required for building the chatbot using the Rasa framework were successfully installed and verified.
