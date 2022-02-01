
<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=E51C44&labelColor=0A1033">

 <img src="https://img.shields.io/static/v1?label=NLW&message=06&color=E51C44&labelColor=0A1033" alt="NLW 06" />
</p>


![cover](.github/cover.png?style=flat)


## 💻 Projeto
Um projeto extremamente simples de e-commerce (ainda incompleto) feito com Django 4.0.2 e Python 3.10.2.

## ✨ Tecnologias

-   [ ] Python
-   [ ] Django
-   [ ] Html
-   [ ] Css
-   [ ] JavaScript
-   [ ] Mysql
-   [ ] Django Crispy Forms
-   [ ] Django Debug Toolbar
-   [ ] Gunicorn
-   [ ] Pillow



## 🔖 Deploy

Você pode visualizar o Deploy do projeto através [desse link](https://github.com/Felipe-007/Ecommerce.git).


## Tutorial para iniciantes

Abaixo uma lista de comandos para clonar e configurar este projeto na sua 
máquina local:

- Instalar git (Windows, Linux e Mac) e depois:

```
git clone https://github.com/Felipe-007/Ecommerce.git
```

- Para **Windows**:

```
cd Ecommerce
python -m venv venv
venv\Scripts\activate.bat
pip install -r requirements.txt
configurar o mysql, conforme ícone abaixo
python manage.py migrate
python manage.py loaddata db.json
python manage.py runserver
```

- Para **Linux**:

```
cd Ecommerce
python3.7 -m venv venv
. venv/bin/activate
pip install -r requirements.txt
configurar o mysql, conforme ícone abaixo
python manage.py migrate
python manage.py loaddata db.json
python manage.py runserver
```

- Para **Mac**

```
cd Ecommerce
python -m venv venv
. venv/bin/activate
pip install -r requirements.txt
configurar o mysql, conforme ícone abaixo
python manage.py migrate
python manage.py loaddata db.json
python manage.py runserver
```

## :hammer_and_wrench: Mysql 
Caso apresente erro durante a migração "python manage.py migrate", crie o arquivo local_settings.py na pasta \Ecommerce\loja.
Com a seguintes configurações:

```
DEBUG = True

ALLOWED_HOSTS = []

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'ecommerce_django',
        'USER': 'root',
        'PASSWORD': '',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
```
Realize a configuração do seu banco de dados, referenciando as configurações acima.

Pronto!


## 📄 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

<br />

<div align="center">
  <small>Agradecimentos ao professor Luiz Otávio Miranda</small>  
</div>
