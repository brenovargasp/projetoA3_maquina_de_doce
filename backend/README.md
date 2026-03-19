Para rodar o código: 

1. python -m venv .venv
2. .venv\Scripts\Activate.ps1
3. python install -r requirements.txt
4. python -m uvicorn backend.app.main:app --reload