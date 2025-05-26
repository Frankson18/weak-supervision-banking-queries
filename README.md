# Rotulagem com Weak Supervision em Consultas Bancárias

Este trabalho tem como objetivo aplicar técnicas de *Weak Supervision* para rotular automaticamente dados de clientes em consultas bancárias, utilizando o dataset [banking77](https://huggingface.co/datasets/PolyAI/banking77).

## 🔍 Descrição

O trabalho foi inspirado no artigo [Stronger Than You Think: Benchmarking Weak Supervision on Realistic Tasks](https://arxiv.org/pdf/2501.07727) que traz a perrogativa que os benchmarks de weak supervision precisam de datasets que transmitam a complexidade de situações reais. No artigos os autores usam varios dataset para cria um novo benchmark mostrando o real poder da weak supervision. O dataset `banking77` foi um dos utilizados no artigo, sendo composto por frases de usuários a sistemas bancários.

Neste trabalho, são utilizados:

- Técnicas de weak supervision para geração de rótulos
- Métricas para avaliação da qualidade dos rótulos
- Visualizações para análise exploratória dos dados

## 🧪 Tecnologias Utilizadas

- [Python](https://www.python.org/)
- [Poetry](https://python-poetry.org/) para gerenciamento de dependências e ambiente virtual
- [Dev Containers](https://containers.dev/) para desenvolvimento reproduzível em ambientes isolados (VS Code + Docker)

## 🚀 Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/seu-repo.git
cd seu-repo
```

2. Abra no VS Code com suporte a Dev Containers:
```
Reabra no Container
```

3. Ou configure localmente com Poetry:
```bash
poetry install
poetry shell
```
4. Crie variaveis de ambiente

```
Crie o arquivo .env com as 2 variavies, caso queira roda na integrar, baixando os dataset novamente ou rodando o gemini:
HF_TOKEN='sua API_KEY'
GOOGLE_API_KEY='sua API_KEY'
```
5. Execute o notebook:
```bash
jupyter notebook
```

## 📚 Referências

- [Stronger Than You Think (Arxiv)](https://arxiv.org/pdf/2501.07727)
- [Dataset banking77 - HuggingFace](https://huggingface.co/datasets/PolyAI/banking77)
