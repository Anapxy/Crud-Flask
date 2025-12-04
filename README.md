# CRUD Flask (SQLite)

Este projeto é um CRUD simples em Flask usando SQLite.

## Como rodar

Pré-requisitos: Python 3.9+.

### macOS/Linux (zsh/bash)

```zsh
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python form_db.py   # cria/zera o banco form_db.db
python app.py       # inicia o servidor
```

Acesse em <http://127.0.0.1:5000>

### Windows (PowerShell)

### Windows (PowerShell)

```powershell
1- instalar o Python
2 - Instalar o  VS Code
3 - criar ambiente virtual: 
python -m venv .venv

4 - Ativar ambiente virtual:
.venv/scripts/activate

5 - Instalar o Flask:
pip install flask

6 - Criar BD:
python db_smarteventos.py   # cria/zera o banco form_db.db

7 - Rodar o software:
python app.py       # inicia o servidor

Obs: Para parar o servidor CTRL + C
```

Se a ativação da venv for bloqueada, abra o PowerShell e execute:

```powershell

Set-ExecutionPolicy -Scope CurrentUser RemoteSigned

```

### Windows (Prompt de Comando - CMD)

python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python form_db.py   # cria/zera o banco form_db.db
python app.py       # inicia o servidor

```

Para parar o servidor: CTRL+C. 

Para sair da venv: `deactivate`.

 
## Observações
 
- O log 404 para `/favicon.ico` é esperado se não houver um favicon configurado e não afeta o funcionamento.
