1. Get the virtualenv path:

```bash
poetry env use python
```



---

2. Run REST API:

```
cd bddtter
poetry run python3 app.py
```

3. Run tests

```
poetry run behave --tags=@rest
poetry run behave --tags=@lru
poetry run behave --tags=@mock

poetry run behave
```
