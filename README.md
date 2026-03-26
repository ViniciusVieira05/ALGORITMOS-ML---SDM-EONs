# ALGORITMOS-ML---SDM-EONs

# Classificação de Conexões em Redes Ópticas Elásticas com Machine Learning

---

## Sobre o Projeto

Este repositório apresenta a implementação de modelos de Machine Learning aplicados à classificação da viabilidade de conexões em Redes Ópticas Elásticas (EONs). O objetivo é utilizar técnicas de aprendizado supervisionado para auxiliar na decisão de aceitação ou bloqueio de conexões, considerando limitações da rede e parâmetros da camada física.

A base de dados utilizada foi gerada por meio de simulação computacional utilizando o simulador SNetS, permitindo a análise de cenários realistas de operação de redes ópticas.

Os modelos são treinados a partir de métricas relevantes como:
- Optical Signal-to-Noise Ratio (OSNR)
- Crosstalk (interferência entre núcleos)
- Formato de modulação
- Alocação de slots espectrais

O principal objetivo deste repositório é garantir a reprodutibilidade dos experimentos e servir como base para estudos futuros na área.

---

## Algoritmos Avaliados

Os seguintes modelos de classificação foram implementados e avaliados:

- Regressão Logística
- Árvore de Decisão

---

## Estrutura do Repositório

# Classificação de Conexões em Redes Ópticas Elásticas com Machine Learning

Python • Jupyter Notebook • Scikit-Learn • Pandas • Google Colab

---

## Sobre o Projeto

Este repositório apresenta a implementação de modelos de Machine Learning aplicados à classificação da viabilidade de conexões em Redes Ópticas Elásticas (EONs). O objetivo é utilizar técnicas de aprendizado supervisionado para auxiliar na decisão de aceitação ou bloqueio de conexões, considerando limitações da rede e parâmetros da camada física.

A base de dados utilizada foi gerada por meio de simulação computacional utilizando o simulador SNetS, permitindo a análise de cenários realistas de operação de redes ópticas.

Os modelos são treinados a partir de métricas relevantes como:
- Optical Signal-to-Noise Ratio (OSNR)
- Crosstalk (interferência entre núcleos)
- Formato de modulação
- Alocação de slots espectrais

O principal objetivo deste repositório é garantir a reprodutibilidade dos experimentos e servir como base para estudos futuros na área.

---

## Algoritmos Avaliados

Os seguintes modelos de classificação foram implementados e avaliados:

- Regressão Logística
- Árvore de Decisão
---

## Instruções de Uso

### 1. Clonagem do Repositório:

  ```bash
  git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

### 2. Execução no Google Colab
Os notebooks podem ser executados diretamente no Google Colab:

Acesse o Google Colab.
Vá em "Arquivo" > "Abrir notebook".
Selecione a aba "GitHub" e insira a URL do repositório.
Escolha o notebook desejado.
### 3. Preparação dos Dados
Para execução correta:

Crie uma pasta chamada data no ambiente do Colab.
Faça o upload dos arquivos de dados presentes neste repositório.
### 4. Execução
Execute as células dos notebooks de forma sequencial, observando os comentários e as etapas de pré-processamento, treinamento e avaliação dos modelos.

### Contribuição
Este repositório tem como objetivo principal a reprodutibilidade científica. Melhorias, ajustes e extensões dos experimentos são bem-vindos, desde que mantenham a organização e clareza do projeto.

---

### Autores
Desenvolvido por Vinicius Vieira Romão, sob orientação de Jurandir Cavalcante Lacerda Júnior, responsável também pelo fornecimento da base de dados utilizada nos experimentos.
