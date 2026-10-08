# Demo Django + Tailwind + Docker

Projeto desenvolvido como parte das atividades da disciplina de Programação Web. A aplicação consiste em um site dinâmico simples utilizando **Django**, estilizado com **Tailwind CSS** (via CDN), dados armazenados em banco de dados **SQLite** e ambiente orquestrado com **Docker**.

---

## Autor

- **Nome:** Gustavo Zacarias Souza
- **Curso:** Ciência da Computação
- **Matrícula:** 22.1.4112
- **Disciplina:** Programação Web (BCC481)
- **Instituição:** Universidade Federal de Ouro Preto (UFOP)

---

## Tecnologias Utilizadas

- [Python 3.12](https://www.python.org/)
- [Django 5.1](https://www.djangoproject.com/)
- [Tailwind CSS](https://tailwindcss.com/) (CDN)
- [SQLite](https://www.sqlite.org/)
- [Docker](https://www.docker.com/) & [Docker Compose](https://docs.docker.com/compose/)

---

## Como Executar o Projeto

1. **Clonar o repositório:**
   ```bash git clone [https://github.com/guzsouza/demo-django.git](https://github.com/guzsouza/demo-django.git)
   ```bash cd demo-django

2. **Subir os containers Docker**
    ```bash docker compose up --build

3. **Acessar a aplicação:**
    Página Inicial: http://localhost:8000/
    Página Sobre: http://localhost:8000/sobre/
    Painel Administrativo: http://localhost:8000/admin/

4. **Criar um superusuário no Django (Admin):**
    ```bash docker compose exec web python manage.py createsuperuser
    