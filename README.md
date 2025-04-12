# 🧠 SOM e MLP - Predição e Agrupamento de Risco de Ataque Cardíaco

Português (Brasil) | English (US)

---

## 🇧🇷 Português (Brasil)

Este projeto foi desenvolvido como parte da disciplina de **Redes Neurais**, com foco na análise e predição do risco de ataque cardíaco. A atividade foi dividida em duas etapas:

- 🧠 **Classificação binária com MLP (Multi-Layer Perceptron)**  
- 🧩 **Agrupamento não supervisionado com SOM (Self-Organizing Maps)**

Utilizamos o framework **TensorFlow/Keras** para a construção do classificador e a biblioteca **MiniSom** para os mapas auto-organizáveis.

---

## 📊 Sobre o Conjunto de Dados

O **Heart Attack Risk Prediction Dataset** contém dados clínicos, comportamentais e demográficos dos pacientes, como:

- Idade, gênero, tabagismo, consumo de álcool
- Níveis de colesterol, triglicerídeos e pressão arterial
- Histórico familiar e diagnóstico de doenças como diabetes e obesidade
- Hábitos alimentares, nível de atividade física e estresse

O dataset foi normalizado com `MinMaxScaler` e processado com `get_dummies()` para variáveis categóricas.

---

## 🎯 Objetivos

### MLP (Rede Neural Supervisionada)
- Treinar um modelo de classificação binária para prever risco de ataque cardíaco
- Avaliar o modelo com métricas como **acurácia**, **AUC**, **perda** e **matriz de confusão**
- Implementar regularização com `Dropout` e monitorar o desempenho com gráficos

### SOM (Aprendizado Não Supervisionado)
- Aplicar Mapas Auto-Organizáveis para **visualizar agrupamentos naturais** nos dados
- Calcular **Quantization Error** e **Topographic Error**
- Explorar visualizações como **Hit Map**, **U-Matrix** e **Component Planes**
- Comparar os padrões extraídos com os resultados do MLP

---

## 🔍 Tecnologias Utilizadas

- Python 3.11
- TensorFlow & Keras
- scikit-learn
- imblearn (SMOTE)
- matplotlib
- MiniSom

---

## 📁 Organização do Notebook

1. Introdução e descrição do dataset
2. Pré-processamento dos dados
3. Treinamento do SOM e visualizações
4. Treinamento do MLP e avaliação
5. Comparação final dos resultados

---

## ✨ Feito com carinho para um projeto de classe.

---

## 🇺🇸 English (US)

This project was developed for the **Neural Networks** course and focuses on analyzing and predicting heart attack risk using:

- 🧠 **Binary classification with MLP (Multi-Layer Perceptron)**  
- 🧩 **Unsupervised clustering using SOM (Self-Organizing Maps)**

We used **TensorFlow/Keras** for the neural network model and **MiniSom** for the self-organizing maps.

---

## 📊 About the Dataset

The **Heart Attack Risk Prediction Dataset** includes a variety of medical, behavioral, and demographic features, such as:

- Age, gender, smoking, alcohol consumption
- Cholesterol, blood pressure, and triglyceride levels
- Family history and conditions like diabetes and obesity
- Diet, physical activity, and stress levels

The dataset was normalized and categorical variables were encoded.

---

## 🎯 Objectives

### MLP (Supervised Neural Network)
- Train a binary classification model to predict heart attack risk
- Evaluate performance with **accuracy**, **AUC**, **loss**, and **confusion matrix**
- Use `Dropout` and training visualization to monitor learning

### SOM (Unsupervised Learning)
- Use Self-Organizing Maps to **visualize natural groupings**
- Calculate **Quantization Error** and **Topographic Error**
- Display **Hit Map**, **U-Matrix**, and **Component Planes**
- Compare clustering patterns with MLP results

---

## 🔍 Technologies Used

- Python 3.11
- TensorFlow & Keras
- scikit-learn
- imblearn (SMOTE)
- matplotlib
- MiniSom

---

## 📁 Notebook Outline

1. Dataset overview
2. Data preprocessing
3. SOM training and visualization
4. MLP training and evaluation
5. Final comparison and analysis

---

## ✨ Made with care for a class project.


Bruna Melido
