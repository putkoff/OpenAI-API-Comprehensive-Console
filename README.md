# OpenAI API Interaction Functions

This repository contains several utility functions to interact with different versions of the OpenAI API.
![image](https://github.com/putkoff/OpenAI-API-Comprehensive-Console/assets/57512254/54470516-b51e-4539-88cf-462b80ea149b)

## Token Info Function

```python
def get_token_info():
    ...
```
This function returns a dictionary of various OpenAI models along with the maximum token counts that they can handle.

## EndPoints Function

```python
def endPoints():
    ...
```
This function returns the different endpoints for the OpenAI API that correspond to different functionalities, along with the models that can be used with them.

## Models Function

```python
def get_models(endpoint):
    ...
```
This function returns the models that are compatible with a particular endpoint.

## Truncate Text Function

```python
def truncate_text(text, max_tokens):
    ...
```
This function truncates a given text to a specified maximum number of tokens while preserving the integrity of sentences or words.

## Filling Tokens Function

```python
def fill_toks(string, max_tokens):
    ...
```
This function fills a list with substrings of a given string based on a specified token count.

## Finding Tokens Function

```python
def find_toks(text, desired_tokens):
    ...
```
This function finds the positions to split a text into chunks based on a desired token count.

## Token Counting Function

```python
def count_tokens(text):
    ...
```
This function uses the Natural Language Toolkit (NLTK) library to count the number of tokens in a text.

---

# GUI Functions

A set of functions that perform various operations on the graphical user interface (GUI).

---

# Prompt and Chunk Manipulation Functions

A set of functions that prepare the prompt and manipulate the chunks of text based on user input and the selected AI model.

---

# Miscellaneous Functions

A set of miscellaneous functions to assist with various operations such as running shell commands, copying text to the clipboard, and retrieving text from the clipboard.

---

For detailed usage of each function, kindly refer to the source code. You will also find comments in the code explaining the purpose and usage of each function.

## Requirements

To run the functions in this repository, you will need Python 3 and the following packages:

- NLTK
- PySimpleGUI
- Requests
- BeautifulSoup
- Pyperclip

You can install these packages using pip:

```bash
pip install nltk PySimpleGUI requests beautifulsoup4 pyperclip
```

---

## License

This project is open-source and available under the MIT License.

---

## Contributing

If you wish to contribute, please create a new issue or a pull request.

---

## REQUIREMENTS.TXT

glob2==0.7
collections-extended==1.0.3
openai==0.27.0
json5==0.9.6
os-sys==2.1.4
requests==2.26.0
PySimpleGUI==4.45.0
pyperclip==1.8.2
nltk==3.6.2
beautifulsoup4==4.9.3

---
