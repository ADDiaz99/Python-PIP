# Game Project

Para correr el juego debes seguir las siguientes instrucciones en la terminal

```sh
cd game 
python3 main.py
```


# App Project

```sh
git clone
cd app
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
python3 main.py
```



# Docker Support
El web-server es con base en FastAPI, y junto a "App" son compatibles con environments en Docker, comandos:
```sh
docker compose build
docker compose up -d
docker compose ps
docker compose exec app-csv bash

```