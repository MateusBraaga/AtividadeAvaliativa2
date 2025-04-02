# AtividadeAvaliativa2
Introdução ao MachineLearning e Kaggle
##########################################
# 🚢 Predição de Sobrevivência no Titanic

## 📌 Introdução
Este projeto utiliza a base de dados pública do Titanic, disponível no Kaggle, para desenvolver um modelo de Machine Learning que prevê a sobrevivência dos passageiros com base em diferentes características, como idade, sexo, classe da passagem, entre outras.

## 🗂️ Descrição da Base de Dados
O conjunto de dados contém informações detalhadas sobre os passageiros do Titanic, incluindo:

- `Survived`: Indica se o passageiro sobreviveu (1) ou não (0).
- `Pclass`: Classe da passagem (1ª, 2ª ou 3ª classe).
- `Sex`: Sexo do passageiro (masculino/feminino).
- `Age`: Idade do passageiro.
- `SibSp`: Número de irmãos/cônjuges a bordo.
- `Parch`: Número de pais/filhos a bordo.
- `Fare`: Tarifa paga pela passagem.
- `Embarked`: Porto de embarque (C = Cherbourg, Q = Queenstown, S = Southampton).

O objetivo é prever a variável **"Survived"**, identificando quais fatores influenciaram a sobrevivência dos passageiros.

## 🎯 Técnica de Machine Learning Escolhida
Para este problema, utilizamos **classificação**, pois a variável de saída (**Survived**) é binária (0 = Não sobreviveu, 1 = Sobreviveu).  

O modelo escolhido foi o **Random Forest**, um algoritmo poderoso para problemas de classificação, pois:  
✔️ Lida bem com dados categóricos e numéricos.  
✔️ Reduz o risco de overfitting ao combinar múltiplas árvores de decisão.  
✔️ Tem alto desempenho em conjuntos de dados pequenos e médios.  

## 📊 Objetivo da Análise
O objetivo deste estudo é entender quais fatores tiveram maior impacto na sobrevivência dos passageiros do Titanic. Para isso, o modelo de classificação será treinado e avaliado com métricas como **acurácia, matriz de confusão e relatório de classificação**.

## 🖥️ Como Reproduzir a Análise
1. Clone este repositório:  
   ```bash
   git clone https://github.com/seu-usuario/titanic-ml.git

