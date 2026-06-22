# Chirayu Mahajan

**Mostly Python, occasionally C, always trying to ship the thing instead of leaving it half-built.**

Right now that means computer vision fundamentals, a couple of backend projects, and figuring out how agents actually work under the hood.

---

## About

BTech student, mostly self-taught past the coursework. My projects so far cover authentication infrastructure, a voice assistant, and an NLP preprocessing tool, and I'm now extending that into computer vision and agent-based systems.

I tend to pick the version of a project that has more moving parts, even when a simpler version would technically satisfy the assignment — splitting Pay-Trust into two separate services instead of one was that kind of decision. I like the parts of a project where something breaks in a way the tutorial never mentioned — that's usually where I learn the most.

---

## Currently Learning

- LLM agent architectures and tool-use orchestration
- Computer vision fundamentals and model fine-tuning
- Backend system design for AI-serving infrastructure

---

## Current Focus

Right now I'm working on strengthening my computer vision fundamentals (OpenCV, image processing pipelines) and exploring how to combine vision models with language models in a single working system. Alongside that, I'm building out backend skills — APIs, real-time communication, deployment — so I can ship these systems myself instead of relying on someone else's infrastructure.

---

## Featured Projects

**[Pay-Trust](https://github.com/Chirayu1167/Pay-Trust)**
OTP-based payment authentication platform with a FastAPI backend and a separate WebSocket service for real-time session state. Splitting the WebSocket layer out from the FastAPI backend seemed like overkill until I actually had to debug a session going stale across both services at once.

**[Phoenix AI Assistant](https://github.com/Chirayu1167/Pheonix-AI-Assistant)**
Voice-first assistant with wake-word detection, speech recognition, and text-to-speech, wrapped in a desktop GUI. Kept the voice pipeline local instead of calling a cloud API for every step — the assistant feels faster, but I had to accept worse recognition accuracy than a cloud model would give.

**[Neurix](https://neurix-nlp-001bychirayu.streamlit.app/)**
NLP preprocessing tool — cleaning, tokenization, and structuring raw text into a form ready for downstream modeling. Wrote the preprocessing as its own module instead of a script I'd copy-paste, mostly because I was tired of rewriting the same cleaning logic for every new NLP idea.

---

## Engineering Interests

Most of what pulls me in right now is vision and language models working together, and the backend work needed to actually run them somewhere other than my laptop.

---

## Technical Skills

**Languages**
Python · C · C++

**AI / ML**
NumPy · Pandas · scikit-learn · NLP · Data Processing

**Computer Vision**
OpenCV *(learning)*

**Backend**
FastAPI · Flask · REST APIs · WebSockets

**Cloud & Deployment**
AWS · Firebase · Railway · Render · Vercel · Cloudflare · Streamlit

**Databases**
MySQL

**Developer Tools**
Git · GitHub · Streamlit · Anaconda

---

## GitHub Activity

![Chirayu's GitHub stats](https://github-readme-stats.vercel.app/api?username=Chirayu1167&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Chirayu1167&layout=compact&theme=tokyonight&hide_border=true)

---

## What I Want to Build Next

I want to build something where a vision model and a language model are working on the same problem together, not just side by side. After that, I want to get better at the backend side of running these things — the parts that don't show up in a notebook.

---

## Connect

[LinkedIn](https://linkedin.com/in/chirayu-mahajan-390766309) · [Email](mailto:mahajanchirayu1167@gmail.com)
