
#Motivation

I wanted to create a chat clone of myself.
chatting with my clone when im down, rememvering what were the things I put importance on, etc.
but man fine-tuning LLM with chat history is extremely stressful.
GPTs only accepts 20 small files.
c.ai, Delphi.ai, Replika doesnt even allow users to fine-tune with original dataset.
fine-tuning GPT or other LLM is only accepts dataset in a specific format and cleaning task for each chat app history is nightmare.
so I built this.
The app is not done yet.
There are so many things I wanna add like supporting other chat app, increase the fine-tuning quality, improve chat experience etc.
If you are interested in relationship building between Human and Machine too, feel free to reach me out @ https://twitter.com/koheingt

#Overview

This application allows users to create their chat clone for engaging chat experiences. By uploading their chat history, users can craft an chat clone that embodies their values and behaviors, offering a unique and tailored interaction.

#Key Features
- Upload chat history from WhatsApp, Telegram, and Instagram Messenger
- Clean and reformat chat history for preparing dataset
- Fine-tune a chat model based on users chat history
- Engage in conversations with the your chat clone through a web interface

Getting Started

#Prerequisites
- Node.js
- Python 3
- Flask
- OpenAI API key

#Installation

1: Clone the repository to your local machine.

2: Install Node.js dependencies

npm install

3: Install Python dependencies

pip install flask openai flask_cors

4: Set up OPENAI_API_KEY
go to https://platform.openai.com/ and create your account, move to API KEY tab, create a secret key and copy it
go to .env file and paste the key like this ""

#Start Your Application

1: Start the Node.js server
go to Terminal
cd to clone-factory-v1

node app.js

2: Start the Flask server
open another Terminal
cd to clone-factory-v1

export FLASK_APP=chat_with_model.py
flask run

3: Play with the app
Open your web browser and navigate to http://localhost:3000
Play with the app
