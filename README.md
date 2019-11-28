# sistema_django

Criando um projeto em Django

1 - Clone esse repositório;

```
git clone git@github.com:fabiano-moreira/sistema_django.git

```

2 - Crie um ambiente virtual para instalar os pacotes e não misturar com a estrutura do seu sistema.
Em seguida, ative o virtualenv;

```
$ cd sistema_django
$ python3 -m venv .venv
$ source .venv/bin/activate
```

3 -  Instale as dependências;

```
(.venv)$ pip install -r requirements.txt

```

4 - Rode as migrações:

```
(.venv)$ python manage.py migrate

```
5 - Crie um usuário administrador para o Django:

```
(.venv)$ python manage.py createsuperuser
```

6 - Para rodar o projeto, execute o comando abaixo e acesse o ip e porta informados:

```
(.venv)$  python manage.py runserver
```
