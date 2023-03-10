# ChatBoy

*the no BS chatwrapper you always wanted*

or as the ChatBoy himself would say:

*An intelligent chatbot powered by advanced AI and natural language processing technology. Capable of understanding context, recognizing user intents, and generating personalized responses in real-time. Designed to assist users with a wide range of inquiries and provide relevant and helpful assistance. Developed using machine learning algorithms and data-processing, this chatbot is continuously evolving to improve its performance and user interactions.*

<br>

#### Prerequisites
- Python 3.8+
- Node v19.7.0 (younger versions might be fine also)
- NPM 9.5.0 (younger versions might be fine also)

#### Install
```bash
git clone git@github.com:andreasoie/chatboy.git && cd chatboy
```

###### Backend
```bash
cd backend
virtualenv venv && source venv/bin/activate
pip install -r requirements.txt
```

Add your `API_KEY` to an .env file, then start server with:
```bash
uvicorn main:app --reload
```
<br>

###### Frontend
```bash
cd frontend
npm install
```
start with:
```bash
npm run dev
```
<br>

## Previews

###### 1) Intutive UI
<p float="left">
  <img src="docs/loading.png" width="100%"/>
</p>

###### 2) Understands all the nonsense you throw at it
<p float="left">
  <img src="docs/theory.png" width="100%"/>
</p>

###### 3) Supports highlighting
<p float="left">
  <img src="docs/code.png" width="100%"/>
</p>
