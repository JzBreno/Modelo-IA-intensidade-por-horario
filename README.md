# Análise de Movimento e Intensidade Luminosa

Este projeto utiliza um conjunto de dados de um parque de iluminação pública para analisar a intensidade luminosa e a movimentação das luminárias. O objetivo é simular e prever a intensidade luminosa com base no movimento em diferentes horários do dia, utilizando um modelo de regressão linear.

## Índice

- [Descrição](#descrição)
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Como Usar](#como-usar)
- [Metodologia](#metodologia)
- [Resultados](#resultados)
- [Licença](#licença)

## Descrição

O projeto consiste em diversas etapas que incluem:

1. **Importação e Limpeza de Dados**: Leitura e análise de um conjunto de dados relacionado a um parque de iluminação pública.
2. **Geração de Dados de Movimentação e Intensidade**: Simulação de movimentos aleatórios das luminárias e cálculo da intensidade luminosa.
3. **Modelagem**: Treinamento de um modelo de regressão linear para prever a intensidade luminosa com base nos dados de movimentação.
4. **Visualização**: Criação de gráficos para visualizar a intensidade luminosa estimada e a movimentação ao longo do tempo.

## Pré-requisitos

- Python 3.x
- Pacotes necessários:
  - pandas
  - numpy
  - matplotlib
  - scikit-learn

## Instalação

Clone o repositório e instale os pacotes necessários:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
pip install -r requirements.txt
```

> **Nota:** Certifique-se de ter o arquivo de dados `relatoriodoparquedeiluminacaopublica.xlsx` disponível na pasta correta.

## Como Usar

Execute o script para gerar o modelo e visualizar os resultados:

```bash
python seu_script.py
```

O script realizará as seguintes operações:
- Lerá os dados do arquivo Excel.
- Limpará e analisará os dados.
- Simulará movimentações e calculará a intensidade luminosa.
- Treinará um modelo de regressão linear.
- Criará gráficos que mostram a estimativa da intensidade luminosa e a média de movimentação por hora.

## Metodologia

### 1. Importação e Limpeza de Dados

O projeto começa importando os dados de um arquivo Excel e verificando informações como tipos de dados e presença de valores nulos.

### 2. Análise de Dados

Os dados são analisados para entender a distribuição das potências nominais das luminárias e a quantidade total de luminárias.

### 3. Geração de Dados Aleatórios

A movimentação das luminárias é simulada usando uma distribuição de Poisson, e a intensidade luminosa é calculada com base nesse movimento.

### 4. Modelagem

Um modelo de regressão linear é treinado com os dados de movimentação e hora, e é utilizado para prever a intensidade luminosa.

### 5. Visualização

Gráficos são gerados para mostrar as estimativas de intensidade luminosa e a distribuição das ocorrências de movimentação por hora.

## Resultados

O projeto gera dois gráficos principais:

- **Estimativa da Intensidade Luminosa por Hora**: Mostra a intensidade luminosa prevista ao longo do tempo.
- **Distribuição das Ocorrências de Movimentação por Hora**: Exibe a média de movimentação ao longo do tempo.

Esses gráficos permitem visualizar a relação entre o movimento e a intensidade luminosa em diferentes horários.


