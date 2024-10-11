# PYTHON-DJANGO-API

Para executar o projeto:

# 🐍 INSTALAÇÃO DO DJANGO 
$ python3 -m pip install Django

🖱️ Criando Projeto
$ django-admin startproject nome_projeto

🖱️ Criando App
$ python3 manage.py startapp nome_app

# 🎲 Atualizando Banco de Dados
$ python3 manage.py makemigrations 

🖱️ o arquivo sql com a estrutura do banco de dados é criado.

$ python3 manage.py migrate

🖱️ executa o arquivo sql no banco de dados

# 🖥️ Manipulando o django pelo terminal
$ python3 manage.py shell


# 📝 Colinhas

> Importação das classes
> 
from usuario.models import Aluno, Disciplina, Curso, Professor....

> Criando os objetos

user = Usuario (nome = "Leticia Mussolin", ...)

> Salvando cada um dos objetos
> 
user.save()

