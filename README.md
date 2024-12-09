# Cálculo de Similaridade entre Políticas e Ações Orçamentárias

Este repositório contém um script e um arquivo de resultados utilizados para calcular similaridades entre políticas públicas e ações orçamentárias. A análise foi feita utilizando técnicas de Processamento de Linguagem Natural (PLN) e embeddings textuais com o modelo **paraphrase-multilingual-mpnet-base-v2**.

## Estrutura do Repositório

- `Plano Brasil Sem Fome.py`: Script Python utilizado para realizar o cálculo de similaridade.
- `saída_correspondencias.csv`: Resultado gerado pelo script, contendo as similaridades calculadas entre as políticas e as ações.

## Requisitos para Execução

Antes de rodar o script, certifique-se de que as bibliotecas abaixo estão instaladas:

- `pandas`
- `scikit-learn`
- `transformers`
- `torch`
- `numpy`

Você pode instalar as dependências executando o seguinte comando:

```bash
pip install pandas scikit-learn transformers torch numpy
