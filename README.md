# Desenvolvimento de api
-- finalidade aprensentação de habilidades 
-- tempo de produção  3 a 4 dias com dados basicos

1. 🔁 Clone o projeto

Se estiver no GitHub:

git clone https://github.com/seu-usuario/seu-repo.git
cd seu-repo

2. 📦 Instalar o Poetry

Se a pessoa ainda não tiver o Poetry instalado:

curl -sSL https://install.python-poetry.org | python3 -

    Depois disso, feche e abra o terminal, ou rode: source $HOME/.poetry/env

3. 🧰 Instalar as dependências

No diretório do projeto:

poetry install

    Isso lê o pyproject.toml e instala exatamente os pacotes e versões definidos no poetry.lock.

4. 🏃 Ativar o ambiente virtual

poetry shell

5. 🚀 Rodar o projeto

Se for rodar o servidor FastAPI:

uvicorn main:app --reload

    Isso assume que seu main.py tem algo como:

from fastapi import FastAPI

app = FastAPI()

