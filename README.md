# Project Title
Short one-line description of your API + frontend project.

## Contents
- `backend/` or project root: Python API (FastAPI / Flask / Django)
- `frontend/`: React / Vue / Angular frontend
- `README.md`: this file

## Prerequisites
- Python 3.8+ installed
- Node.js 16+ and npm/yarn (for frontend)
- Git

## Setup & Run (Backend)
1. Create and activate a venv (recommended):
   ```bash
   python -m venv venv
   source venv/Scripts/activate   # Git Bash: source venv/Scripts/activate
pip install -r requirements.txt

export ENV_VAR_NAME=value   # on Windows PowerShell use $env:ENV_VAR_NAME="value"

uvicorn main:app --reload --host 0.0.0.0 --port 8000

