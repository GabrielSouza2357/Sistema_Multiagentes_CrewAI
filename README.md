# Sistema Multiagente para Criação de Artigos com CrewAI e Wikipedia

Este projeto utiliza o framework CrewAI para automatizar a criação de artigos para um website. O sistema pesquisa informações relevantes na API da Wikipedia e gera artigos com no mínimo 300 palavras sobre um determinado assunto.

## Tecnologias Utilizadas

- Python
- CrewAI
- crewai-tools
- API da Wikipedia
- Gemini (via `google-generativeai`)
- Flask
- Pydantic

## Pré-requisitos

- Python 3.7 ou superior
- Pip instalado
- Uma chave da API do Google Gemini configurada como variável de ambiente `GOOGLE_API_KEY`
