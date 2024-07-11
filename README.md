# lf-gpt
Experimental work with AI-assisted code generation.

This repository contains the following directories:

1- `all_codebase`: LF files for all target languages, extracted from the Playground repository [https://github.com/lf-lang/playground-lingua-franca].

2- `python_codebase`: LF files for Python target. It's a subdirectory of `all_codebase`.

3- `lib`: LF file implementing an `Accelerometer` reactor for the `C` target. To be used by the `DropSensor` reactor for the `C` target. The `DropSensor` reactor code will be automatically generated in the following.

## Installation
### 1. Python virtual environment`
You should have python3 installed.
Create a virtual environment named `.env`:
```
python3 -m venv .venv
```

### 2. OpenAI API Key
You need an OpenAI Key to use LLMs like gpt-4.
Copy the `.env.example` to `.env`:
```
cp .env.example .env 
```
Edit the `.env` file and add your OpenAI API Key:
```
OPENAI_API_KEY='your_OpenAI_AP_Key'
```

## Run on VScode
1. Open the NoteBook `Context_Engineering4LF.ipynb`.
2. On the right corner click on `select kernel` and choose the `.env` kernel.
3. Run all cells.





