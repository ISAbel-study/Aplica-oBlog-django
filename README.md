# Aplicação Blog com Django 5

Aplicação de blog desenvolvida com **Django 5** para estudo, seguindo os três primeiros capítulos do livro [*Django 5 by Example*](https://djangobyexample.com/) (Antonio Melé, Packt).

## Sobre o Livro Django 5 by example

O livro não apenas aborda os aspectos mais relevantes do framework django, mas também ensina como integrar outras tecnologias aos projetos Django. Dessa forma, ele guia o leitor por todo o processo de desenvolvimento de aplicações web profissionais com o Django. 

A obra apresenta a criação de quatro aplicações do mundo real, a resolução de problemas comuns e implementação as melhores práticas, usando uma abordagem passo a passo fácil de seguir.

Após a ler este livro, o  leitor terá uma boa compreensão de como o Django funciona e de como criar aplicações web práticas e avançadas.

O código de referência do livro está em: https://github.com/PacktPublishing/Django-5-By-Example

## Aplicação de Blog (capítulos 1–3): Criação de uma aplicação blog completa

- Criar modelos de dados, *views* (visualizações) e URLs.
- Implementar um painel de administração para o blog.
- Utilizar URLs canônicas para os modelos e implementar URLs amigáveis para SEO nas publicações.
- Criar a paginação das publicações e aprender a desenvolver *views* baseadas em classes (*Class-Based Views*).
- Utilizar formulários para permitir que os leitores compartilhem publicações por e-mail e implementar um sistema de comentários usando formulários baseados em modelos (*ModelForms*).
- Adicionar tags às publicações utilizando [django-taggit](https://github.com/jazzband/django-taggit) e recomendar publicações semelhantes com base nas tags compartilhadas.
- Implementar *template tags* personalizadas para exibir as publicações mais recentes e as mais comentadas.
- Criar um filtro de template personalizado para renderizar conteúdo em [Markdown](https://github.com/Python-Markdown/markdown).
- Criar um mapa do site (*sitemap*) e um feed RSS para o blog.
- Implementar um mecanismo de busca de texto completo utilizando o PostgreSQL.

## Tecnologias

- Python 3.12+
- Django 5
- django-taggit
- Markdown
- PostgreSQL (necessário para a busca full-text do capítulo 3)

## Como executar

```bash
# 1. Clone o repositório
git clone https://github.com/ISAbel-study/Aplica-oBlog-django.git
cd mysiteblog

# 2. Crie e ative um ambiente virtual
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate

# 3. Instale as dependências
pip install -r requirements.txt

# 4. Aplique as migrações
python manage.py migrate

# 5. Crie um superusuário para acessar o admin
python manage.py createsuperuser

# 6. Inicie o servidor de desenvolvimento
python manage.py runserver
```

Acesse:

- Blog: http://127.0.0.1:8000/blog/
- Administração: http://127.0.0.1:8000/admin/

## Créditos

Projeto baseado no livro *Django 5 by Example*, de Antonio Melé.
