# automacao_py

Automação (fictícia) de cadastro de produtos a partir de um banco de dados.

## Sobre

Este projeto é o resultado de um treinamento da [Hashtag Treinamentos](https://www.hashtagtreinamentos.com/), que ensina a criar automações de tarefas em Python usando a biblioteca [PyAutoGUI](https://pyautogui.readthedocs.io/).

## O que faz

O script `automacao.py` automatiza o cadastro de produtos em um sistema web, realizando as seguintes etapas:

1. Abrir o navegador e acessar o sistema.
2. Fazer login.
3. Importar a base de produtos (`produtos.csv`) com `pandas`.
4. Preencher os campos de cadastro de cada produto usando `pyautogui`.
5. Repetir o processo até o fim da base.

## Arquivos

- `automacao.py` — script principal da automação.
- `pegar_posicao.py` — utilitário para capturar as coordenadas (x, y) do mouse.
- `produtos.csv` — base de dados fictícia com os produtos a cadastrar.

## Requisitos

- Python 3
- `pyautogui`
- `pandas`

Instale as dependências com:

```
pip install pyautogui pandas
```
