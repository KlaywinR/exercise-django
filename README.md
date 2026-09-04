# Exercício Simples de Django

Projeto desenvolvido em Django como atividade acadêmica.

## Descrição

O projeto consiste em uma aplicação Django que apresenta uma mensagem **Hello World!** ao acessar a rota raiz do sistema.

## Tecnologias

* Python
* Django
* Git
* GitHub

## Execução

Clone o repositório e entre na pasta do projeto:

```bash
git clone https://github.com/KlaywinR/exercise-django.git
cd exercise-django
```

Crie e ative o ambiente virtual:

```bash
python -m venv .venv
```

No Windows:

```powershell
.venv\Scripts\Activate.ps1
```

Instale o Django:

```bash
python -m pip install django
```

Execute o servidor:

```bash
python manage.py runserver
```

Acesse:

```text
http://127.0.0.1:8000/
```

## Gitflow

O desenvolvimento foi realizado utilizando o fluxo de branches:

* `main` — versão de produção
* `develop` — desenvolvimento
* `feature/hello-world` — desenvolvimento da funcionalidade Hello World
