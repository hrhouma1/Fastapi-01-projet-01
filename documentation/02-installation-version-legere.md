# Étape 1

```bash
python3 --version
ou python --version
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload --host 0.0.0.0 --port 8000
python seed_data.py add
```

# Étape 2

- Testez /docs => http://localhost:8000/docs


# Étape 3

- Ajout d'un utilisateur par vous même
- Testez ces points de terminaison (endpoints)

```bash
http://127.0.0.1:8000/users/
http://127.0.0.1:8000/items/
http://127.0.0.1:8000/users/1
http://127.0.0.1:8000/users/2
http://127.0.0.1:8000/users/3
http://127.0.0.1:8000/items/
http://127.0.0.1:8000/items/1
http://127.0.0.1:8000/items/2
http://127.0.0.1:8000/items/3
http://localhost:8000/users/5/items/
```


