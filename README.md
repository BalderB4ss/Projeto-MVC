# Instalar o requirements.txt
```bash
pip install -r requirements.txt
```

## Inicializar o alembic
```bash
python -m alembic init migrations
```

## Gerar a migration
```bash
python -m alembic revision --autogenerate -m "Criar tabela usuário"
```
 
## Aplicar a migration
```bash
python -m alembic upgrade head
```

# Rodar o código
```bash
python -m uvicorn app.main:app --reload
```