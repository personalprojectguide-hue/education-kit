# Education Kit

> Flashcards, essay help, study guides, and quiz generators. Learn anything faster.

A multi-tool AI suite with 5 tools, powered by Groq.

---

## Setup

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Rename `.env.example` to `.env` and add your Groq key (get one free at https://console.groq.com).

```bash
uvicorn main:app --reload
```

Open **http://localhost:8000**

---

## Tools included

- **Homework Explainer** — Understand anything, explained simply
- **Personal Statement Writer** — University applications that get offers
- **Flashcard Generator** — Turn any text into study flashcards
- **Maths Problem Solver** — Step-by-step solutions for any maths problem
- **College Application Essay** — Essays that get you into your dream school

Built with [Deplo](https://deplo.app) · Powered by [Groq](https://console.groq.com)
