# Análise de Anomalias de Temperatura da Superfície do Mar (TSM)

Este repositório contém um script em Python para analisar e visualizar as anomalias de Temperatura da Superfície do Mar (TSM) na região Niño 3.4, uma importante variável climática utilizada para monitorar eventos como El Niño e La Niña.

## Objetivo

O script lê um arquivo CSV contendo dados históricos mensais de anomalias de TSM e gera um gráfico que separa visualmente as anomalias positivas (em vermelho) das negativas (em azul). Isso facilita a interpretação dos períodos de aquecimento e resfriamento da superfície oceânica.

## Funcionalidades

- Leitura flexível do arquivo CSV, com exemplos de caminhos para diferentes ambientes: Google Colab, Windows, Linux e MacOS.
- Separação dos valores positivos e negativos das anomalias para análise visual distinta.
- Geração de gráfico de linha simples e claro, com personalização básica.
- Comentários detalhados no código para facilitar o entendimento e possíveis adaptações.

## Como usar

1. **Instale as bibliotecas necessárias**:
   ```bash
   pip install matplotlib pandas
   ```
2. **Prepare seu arquivo CSV** com os dados de anomalia, contendo ao menos uma coluna chamada `ANOM`.
3. **Ajuste o caminho do arquivo CSV no script** conforme seu sistema operacional e ambiente.
4. **Execute o script** para visualizar o gráfico.

## Exemplo de dados esperados

| Mês | ANOM  |
|------|-------|
| 0    | 0.15  |
| 1    | -0.12 |
| 2    | 0.05  |
| ...  | ...   |

## Resultados esperados

- Gráfico com linhas em vermelho para valores positivos (aquecimento) e azul para valores negativos (resfriamento).
- Visualização clara para auxiliar análises climáticas e estudos relacionados ao fenômeno El Niño.
