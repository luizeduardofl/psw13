# 🧠 Insight  

Projeto desenvolvido durante o evento **PYSTACK WEEK 13**, organizado pelo canal do YouTube [Pythonando](https://www.youtube.com/@pythonando).

## ✨ Sobre o projeto

**Insight** é uma aplicação web desenvolvida para facilitar a conexão entre mentores e mentorados, promovendo organização, clareza de objetivos e agendamento de reuniões de forma prática e intuitiva.

### 🎯 Funcionalidades principais

- **Mentores**:
  - Criação de conta na plataforma
  - Disponibilização de horários para agendamento com mentorados
  - Cadastro e acompanhamento de seus mentorados
  - Definição de objetivos individuais para cada mentorado

- **Mentorados**:
  - Acesso por **token único**, sem necessidade de criar conta
  - Visualização dos objetivos definidos pelo mentor
  - Marcação de "check" nos objetivos concluídos

## 🛠️ Tecnologias utilizadas

- **Back-end**: [Python](https://www.python.org/) + [Django](https://www.djangoproject.com/)
- **Front-end**: [Tailwind CSS](https://tailwindcss.com/)
- **Outras bibliotecas**: diversas bibliotecas Python foram utilizadas para facilitar o desenvolvimento (detalhes no `requirements.txt` e nos arquivos do projeto)

## 🚀 Como rodar o projeto

> Requisitos: Python 3.9+, pip

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/mentorconnect.git
cd mentorconnect

# Crie e ative um ambiente virtual
python -m venv venv
source venv/bin/activate  # ou .\venv\Scripts\activate no Windows

# Instale as dependências
pip install -r requirements.txt

# Rode as migrações do Django
python manage.py migrate

# Inicie o servidor
python manage.py runserver
```

## 👨‍💻 Autor

Projeto criado por **Luiz Eduardo** durante o evento **PYSTACK WEEK 13**.

Sinta-se à vontade para contribuir ou adaptar a ideia para seu próprio projeto de mentoria.
