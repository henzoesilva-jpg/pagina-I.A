# pagina.py — Minha Primeira Página com Streamlit

## Descrição

Aplicação web desenvolvida em Python utilizando Streamlit. O projeto apresenta uma interface interativa com campos para inserir peso e altura, além de uma área destinada à apresentação do resultado do cálculo do IMC.

## Requisitos

* Python
* Biblioteca `streamlit`

### Instalação

```bash
pip install streamlit
```

## Configuração do token.json

O arquivo `pagina.py` não utiliza diretamente uma API externa, portanto, não necessita de um arquivo `token.json` para sua execução.

Caso o projeto seja integrado a uma API de inteligência artificial futuramente, será necessário criar o arquivo `token.json` na pasta do projeto.

### Exemplo:

```json
{
    "api_key": "SUA_CHAVE_DA_API"
}
```

## Como executar

No terminal, execute:

```bash
streamlit run pagina.py
```

O navegador abrirá a interface da aplicação.

## Funcionalidades

* Interface web interativa.
* Entrada de peso.
* Entrada de altura.
* Estrutura para cálculo do IMC.
* Apresentação visual utilizando Streamlit.

## Tecnologias utilizadas

* Python
* Streamlit

## Objetivo

Praticar o desenvolvimento de interfaces web utilizando Python e a biblioteca Streamlit.
