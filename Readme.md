# SQLAlchemy & Alembic Demo

### 1- Crie um virtual enviroment para a aplicação
#### $ virtualenv venv
#### $ source venv/bin/activate

### 2 - Instale as libs necessárias
#### $ pip install -r requirements.txt
### ou
#### $ pip install alembic sqlalchemy
### 3 - Configure o ALEMBIC
#### $ alembic init migrations

### 4 - Gere o arquivo de migrations
#### $ alembic revision --autogenerate -m "Create user model"

### 5 - Execute as migrations
#### $ alembic upgrade heads

