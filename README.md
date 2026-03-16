# Chat Service

Minimal setup and CI-ready test target for the Flask chat backend.

## Quickstart

```powershell
python -m venv venv
venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## Run the server

```powershell
python server.py
```

## Run tests

```powershell
pip install -r requirements-dev.txt
pytest -q
```
