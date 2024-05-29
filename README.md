# Atividade: Classificação de Imagens (CIFAR-10)l

Este repositório contém um exemplo de implementação de três técnicas de otimização de modelos de rede neural convolucional, conforme trabalhado em sala de aula. O modelo base utilizado é o mesmo implementado na atividade ponderada da semana 4. As técnicas implementadas são: Data Augmentation, Dropout e Early Stopping.

## Técnicas Implementadas

### 1. Data Augmentation
Data Augmentation é uma técnica usada para aumentar a quantidade e a diversidade dos dados de treinamento ao aplicar transformações aleatórias, mas realistas, às imagens originais. 

### 2. Dropout
Dropout é uma técnica de regularização que ajuda a prevenir overfitting em redes neurais. Durante o treinamento, alguns neurônios são aleatoriamente "desligados" (ou seja, seu valor é ajustado para zero) em cada iteração. Isso força a rede a não depender de neurônios específicos, tornando-a mais robusta.

### 3. Early Stopping
Early Stopping é uma técnica usada para interromper o treinamento do modelo assim que o desempenho no conjunto de validação para de melhorar. 

## Objetivo do Código

O objetivo deste código é demonstrar a aplicação de técnicas avançadas de otimização de modelos de machine learning para melhorar a performance e a generalização de um modelo de rede neural convolucional. Ao utilizar Data Augmentation, Dropout e Early Stopping, o modelo torna-se mais robusto e capaz de lidar com dados não vistos, evitando overfitting e melhorando sua capacidade de generalização.

## Como Usar
Caso queira usar, você pode ter uma cópia do dataset de imagens acessando o link abaixo:
[link](https://drive.google.com/drive/folders/1Mercw3OZ6KJ2h1ZJ5pAOmGuDKelu18RR?usp=sharing)
