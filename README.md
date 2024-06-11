# focus.

A simple producitivity suite made for individuals with ADHD and neurotypicals alike.

## What does this do?
`focus.` is an app written using [pywebview](). It aims to keep you free from distractions and help you study/work in a minimalist and distraction free desktop environment.

## Features
- A simple todo list to start off your day by listing the things you need to do.
- An AI Chatbot that uses RAG on custom documents based on Llama3 and llama_index (powered by [ollama]()).
- Minimalist e-mail client that let's you check your inbox as well quickly draft and send e-mails.


## Roadmap
- Simple note taking app that is added to your RAG dataset for the AI Chatbot
- Music player using youtube-dl
- Smoother interface
- Greater customization and integration with other services like Obsidian/Notion
- Discord rich presence
## Current problems
- Email UI is glitchy
- Distribution
- Requires Python libraries to be installed (stems from previous problem)
- Not really non-programmer friendly

## Prerequisites
1. python 3.9 or above
2. everything in the `requirements.txt` file
3. Ollama with Llama3 installed

## Setup
```sh
git clone https://github.com/divine-architect/focus..git
cd focus.
pip install -r requirements.txt
mkdir data
python focus.py
```
Then make a `.env` file to store environmental variables:
1. `google` - This is your mail app password.
2. `email` - Your email address \

Add your custom dataset/pdfs to the `data` directory to chat with Llama3 about them.
## Gallery
