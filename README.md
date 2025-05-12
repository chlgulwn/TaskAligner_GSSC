# TaskAligner

## 📍Code Description

TaskAligner is an AI-driven tool that analyzes meeting transcripts and team member traits to automatically assign tasks based on individual strengths. 
It combines natural language processing (NLP) with prompt engineering using GPT to generate fair, justifiable task allocations.

## Features

- Supports Korean-language input for meeting transcripts and team traits, while producing all outputs — including summaries and task assignments — in English for international collaboration.
- Structured meeting summarization (task list, team feedback, mentor input, etc.)
- Personality-based task assignment using descriptive trait inputs
- GPT-powered natural language understanding
- Dynamic matching even when "task count ≠ team member count"

## Example Workflow

1. User enters raw meeting transcript
2. System summarizes the meeting and extracts tasks
3. User enters team members' personality traits & Extracted tasks(from step2)
4. AI matches each task to the most suitable team member with reasoning

## Tech Stack

- Python 3.10+
- OpenAI GPT-4o-mini (via API)
- Command-line I/O (interactive CLI)
- Logging module for debugging
