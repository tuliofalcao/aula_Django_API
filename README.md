# aula_Django_API
Aula da Alura - Criando uma API com Django


## Criar ambiente para manter as dependências na pasta do projeto

python3 -m venv ./venv

## Ativar a venv

source venv/bin/activate

## Instalar o Django

pip install django

## (Comando para checar as dependências que foram instaladas)

pip freeze

## Criar aplicação

django-admin startproject config .

## Rodar o servidor

python manage.py runserver

## Abre outro terminal (para deixar o do servidor rodando), inicia o ambiente (venv) e inicia o app

source venv/bin/activate
python manage.py startapp nomedaaplicação

## Criar modelo

/escola/models.py

## Nas configurações (config/settings.py), colocar o app

## Migrar modelo para banco de dados

python manage.py makemigrations
python manage.py migrate




