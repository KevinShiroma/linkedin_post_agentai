# Projeto de Agentes Inteligentes para Coleta de Dados e Criação de Conteúdo

Este projeto utiliza a biblioteca **CrewAI** para criar e gerenciar agentes virtuais que executam tarefas relacionadas à coleta e organização de dados de mercado, pesquisa de notícias e criação de conteúdo digital.

## 🧠 Funcionalidade

O projeto automatiza o processo de:

- Coleta de dados sobre um setor específico
- Busca de notícias relevantes e atualizadas
- Criação de um post para redes sociais como o LinkedIn

Tudo isso feito por agentes inteligentes coordenados por um LLM da OpenAI.

## 🧰 Requisitos

- Python 3.10+
- API Key do [Tavily](https://app.tavily.com/)
- Bibliotecas:
  - `crewai`
  - `python-dotenv`
  - `tavily`
  - `langchain`
  - `langchain_openai`

## 📦 Instalação

Clone o repositório:

```bash
git clone https://github.com/KevinShiroma/linkedin_post_agentai.git
cd seu-repositorio
```

## Crie um ambiente virtual (opcional, mas recomendado):
```bash
python -m venv venv
source venv/bin/activate: .\venv\Scripts\activate
```

## Instale as dependências:
```bash
pip install -r requirements.txt
```

## Crie um arquivo .env na raiz do projeto e adicione sua chave da API do Tavily e da OpenAI
```bash
TAVILY_API_KEY=sua_chave_api
OPENAI_API_KEY=sua_chave_api
```

## 🚀 Como Usar
Execute o código principal para iniciar o processo:

Como é um notebook, só dar um Run All





