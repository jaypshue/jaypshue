# InterviewAssist

> A real-time AI copilot for technical interviews.

Most interview preparation tools help you **before** the interview.

InterviewAssist helps you **during** the interview by listening to the conversation, detecting interview questions, and providing personalized coaching in real time.

---

## Before the Interview

InterviewAssist allows candidates to provide résumé and employer context before the interview begins, enabling more personalized coaching.

![Interview Startup](https://raw.githubusercontent.com/jaysphue/InterviewAssistant/main/docs/images/screenshot_startup.jpg)

---

## During the Interview

As interview questions are detected, InterviewAssist analyzes the conversation and provides concise coaching tailored to both the candidate and the employer.

![Interview Startup](https://raw.githubusercontent.com/jaysphue/InterviewAssistant/main/docs/images/screenshot_active.jpg)


---

# Why InterviewAssist?

Generic AI can answer interview questions.

InterviewAssist understands the interview.

It combines:

- Live interview transcript
- Current interview question
- Candidate résumé and experience
- Employer job description
- Interview history
- AI coaching

to generate responses that are personalized instead of generic.

---

# Features

### Live Transcript

Capture and display interview conversations as they happen.

### Automatic Question Detection

Detect interviewer questions in real time without requiring manual interaction.

### AI Coaching

Provide concise guidance including:

- Key message
- Technical concepts to mention
- Relevant experience to discuss
- Suggested talking points

### Candidate Context

Use résumé information and candidate experience to personalize coaching.

### Employer Context

Analyze the job description to tailor responses to the specific role.

### Live Status

Display interview state in real time:

- Listening
- Question Detected
- Analyzing
- Response Ready

---

# Current Architecture

- ASP.NET Core Web API
- Blazor Server
- SignalR
- OpenAI API
- Docker
- NAudio
- Dependency Injection
- xUnit

---

# Project Structure

```
InterviewAssistant/

├── InterviewAssistant.Api
├── InterviewAssistant.Blazor
├── InterviewAssistant.AudioCapture
├── docs
└── README.md
```

---

# Roadmap

## Completed

- Live transcript pipeline
- Question detection
- AI response generation
- SignalR live updates
- Docker deployment
- Blazor UI
- Unit testing
- Interview orchestration

## In Progress

- Candidate résumé context
- Employer job description context

## Planned

- Candidate Coach
- Practice Interviews
- Persistent Candidate Profile
- Story Library
- Behavioral Interview Coaching
- Live Deployment
- Candidate Profile Learning
- Personalized AI Coaching

---

# Why I Built This

Technical interviews are stressful.

Most AI interview tools prepare candidates **before** the interview.

I wanted to build something that could assist **during** the interview by combining live conversation analysis with personalized coaching based on the candidate's own experience.

InterviewAssist is also an exploration of how AI copilots can maintain context across an entire workflow instead of simply answering isolated prompts.

---

# Running the Project

Clone the repository.

```
git clone https://github.com/<your-github>/InterviewAssistant.git
```

Start the API.

```
docker compose up --build
```

Run the Blazor project.

```
InterviewAssistant.Blazor
```

Open your browser.

```
https://localhost:5001
```

---

# Technologies

- C#
- ASP.NET Core
- Blazor
- SignalR
- OpenAI
- Docker
- NAudio
- xUnit
- Dependency Injection

---

# Future Vision

InterviewAssist is evolving from a technical interview assistant into a personalized interview coach.

Future versions will learn from practice interviews, build a persistent candidate profile, identify strengths and weaknesses, and provide increasingly personalized coaching over time.

The goal is simple:

**Help candidates tell the best version of their own story.**
