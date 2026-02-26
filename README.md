# final-project

## Запуск через [pixi](https://pixi.prefix.dev/latest/installation/)

```bash
pixi install
pixi run dev
```

## Запуск без pixi

**Windows:**
```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
uvicorn src.main:app --reload
```

**Linux/macOS:**
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
uvicorn src.main:app --reload
```

## Ссылки

- API документация: http://localhost:8000/docs
- Альтернативная документация: http://localhost:8000/redoc
