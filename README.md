# Autenticação com OAuth2 - Projeto Django

Este projeto demonstra autenticação OAuth 2.0 no Django, incluindo login social com o Github através do Django Allauth.

---

## ✨ Funcionalidades

- Autenticação social (Github)
- Área exclusiva para membros autenticados
- Interface simples com templates customizados

---

## 🚀 Tecnologias Utilizadas

- Django
- Django Allauth
- HTML + CSS

---

## 📁 Estrutura do Projeto

- `setup/urls.py` — URLs principais
- `tech/urls.py` — URLs do app
- `tech/views.py` — Views de index e área de membros
- `templates/` — Templates HTML (`index.html`, `members.html`)

---

## 🛠️ Como Executar

1. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
2. Rode as migrações:
   ```bash
   python manage.py migrate
   ```
3. Inicie o servidor:
   ```bash
   python manage.py runserver
   ```
4. Acesse `http://localhost:8000` para login via Github ou área de membros.

---

Feito com 💡 para estudos de autenticação Django.