# ChatGPT-HateSpeech

## Repository Contents
This repository contains code for the Ben Gurion University "Natural Language Processing (372.2.5702)" course project. This code was created with <b> Python(3.9.15), pandas, numpy and more libraries</b>.

- Code - [EDA](https://github.com/leorrose/ChatGPT-Hate-Speech/blob/main/eda.ipynb), [Hate speech and target detection](https://github.com/leorrose/ChatGPT-Hate-Speech/blob/main/hate_speech_chat_gpt.ipynb), [Quantitative evaluation](https://github.com/leorrose/ChatGPT-Hate-Speech/blob/main/quantitative_evaluation.ipynb).

- Report - [Report](https://github.com/leorrose/ChatGPT-Hate-Speech/blob/main/report.pdf).

## Project Setup and Run:

1. Clone this repository.
2. Open cmd/shell/terminal and go to project folder: `cd ChatGPT-HateSpeech`
3. Create conda environment: `conda env create -f environment.yml`
4. Create token.txt file and insert you ChatGPT token:
    - Go to [ChatGPT](https://chat.openai.com/api/auth/session)
    - Press F12 to open console
    - Go to Application > Cookies
    - Copy the session token value in __Secure-next-auth.session-token
    - Paste it into token.txt in the current working directory
5. Run each notebook in the environment.

Please let me know if you find bugs or something that needs to be fixed.

Hope you enjoy.
