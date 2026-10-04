# 💬 ChatBot IA com Streamlit e Gemini

Um aplicativo interativo de chat construído em **Python** utilizando **Streamlit** e integrado à API do **Google Gemini** (através da interface compatível da OpenAI).

---

## 🛠️ Tecnologias Utilizadas

- **[Python](https://www.python.org/)**: Linguagem base do projeto.
- **[Streamlit](https://streamlit.io/)**: Framework para criação da interface do chat.
- **[OpenAI Python SDK](https://github.com/openai/openai-python)**: Utilizado para comunicação com os modelos de IA.
- **[Google Gemini API](https://ai.google.dev/)**: Provedor do modelo de linguagem (`gemini-flash-lite-latest`).
- **[python-dotenv](https://github.com/theskumar/python-dotenv)**: Gerenciamento seguro de variáveis de ambiente.

---

## 🚀 Funcionalidades

- 💬 **Interface Intuitiva**: Interface de bate-papo fluida com `st.chat_input` e `st.chat_message`.
- 🧠 **Histórico de Conversa (Memória)**: Armazena o contexto das mensagens enviadas usando `st.session_state`.
- 🔑 **Segurança**: Chave de API protegida em variáveis de ambiente via `.env`.

---

## 📋 Pré-requisitos

Antes de começar, você precisará ter instalado em sua máquina:
- **Python 3.10+**
- Uma chave de API da Google Gemini (Google AI Studio)

---

## 🔧 Configuração e Instalação

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
   cd seu-repositorio


   
