# 🚗 Site de Revenda de Carros

Preview:
![](assets\img\{0BEBFC61-A7B5-4120-AF74-FEE7F59C7B66}.png)



---

## 📖 Sobre o Projeto

Plataforma web para revenda de carros, desenvolvida com Django, HTML e CSS.  
Oferece um sistema completo de autenticação, permitindo que usuários se cadastrem, façam login e gerenciem seus próprios anúncios de veículos.  
É possível **adicionar, editar, excluir e pesquisar carros** de forma simples e intuitiva, tanto pelo site quanto pelo painel administrativo do Django.  
O projeto também conta com **upload de imagens dos veículos**, banco de dados PostgreSQL e utilização de **Django Signals** para executar ações automáticas no sistema, como notificações e registros internos.


---

## ✨ Funcionalidades

- 🔐 **Autenticação**: cadastro, login e logout de usuários  
- 🔍 **Pesquisa avançada**: filtro por marca, modelo, ano, preço, etc  
- 🛠️ **CRUD de carros**: adicionar, editar e excluir anúncios pelo site  
- 🧑‍💼 **Admin Django**: gerenciamento completo via painel administrativo  
- 💾 **Banco de dados SQL** (SQLite por padrão, configurável)  
- ⚡ **Django Signals**: eventos automáticos (ex: notificações, atualizações)  
- 🎨 Interface responsiva em HTML/CSS simples e funcional

---

## 🛠️ Tecnologias Utilizadas

- 🐍 **Python** – Linguagem principal usada no backend do projeto.
- 🕸️ **Django** – Framework web para construção do site e gerenciamento dos dados.
- ⚙️ **PostgreSQL** – Banco de dados da aplicação.
- 🌐 **HTML5** – Estrutura das páginas e marcação de conteúdo.
- 🎨 **CSS3** – Estilização visual e responsividade.
- 🔔 **Django Signals** – Gatilhos automáticos usados para eventos internos do sistema (como notificações ou logs).


---


## 🚀 Como Executar

```bash
# Clonar o repositório
git clone https://github.com/seuusuario/car-resale-django.git
cd car-resale-django

# Criar e ativar ambiente virtual
python -m venv venv

# Linux/macOS
source venv/bin/activate

# Windows
venv\Scripts\activate

# Instalar dependências
pip install -r requirements.txt

# Aplicar migrações do banco
python manage.py migrate

# Criar superusuário admin
python manage.py createsuperuser

# Rodar servidor de desenvolvimento
python manage.py runserver
```
---
## 🔮 Futuras Melhorias

- 📱 Layout mais responsivo e moderno com frameworks frontend, como Tailwind e Bootstrap.
- 📦 Integração com APIs externas para dados de veículos (ex: tabela FIPE)

---

## 📬 Contato

Fique à vontade para entrar em contato caso tenha dúvidas, sugestões ou queira contribuir:
  
- 📨 **Email:** dumedolago@gmail.com 
- 💻 **Linkedin:** [Eduardo Medolago](https://www.linkedin.com/in/eduardo-medolago-364288259/)
