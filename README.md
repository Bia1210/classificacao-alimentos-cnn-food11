# 🍕 Redes Neurais CNN: Classificação de Imagens de Alimentos (Food-11)

Projeto prático de aprendizado profundo (Deep Learning) e Visão Computacional focado no treinamento de uma Rede Neural Convolucional (CNN) para a classificação automática de imagens de alimentos distribuídas em 11 categorias distintas.

## 🎯 Objetivo
Desenvolver, treinar e avaliar um modelo de classificação multiclasse de imagens utilizando o conjunto de dados Food-11, aprendendo representações visuais relevantes para identificação de tipos de comida.

## 🛠️ Tecnologias e Bibliotecas Utilizadas
- **Linguagem:** Python
- **Ambiente de Desenvolvimento:** Google Colab / VS Code
- **Framework de Deep Learning:** TensorFlow / Keras
- **Processamento de Dados e Arquivos:** OS, ZipFile, Random, Shutill
- **Manipulação Numérica e Gráfica:** NumPy, Matplotlib

## 📂 Pipeline do Projeto
1. **Importação e Preparação das Bibliotecas:** Configuração do ambiente com TensorFlow, Keras e módulos de manipulação de diretórios[cite: 5].
2. **Carregamento do Dataset:** Upload e descompactação de arquivos compactados (`.zip`) contendo o conjunto de imagens[cite: 5].
3. **Pré-processamento de Imagens:** Redimensionamento, normalização de tensores e divisão entre conjuntos de treino e validação.
4. **Construção da Arquitetura CNN:** Empilhamento de camadas de convolução (`Conv2D`), pooling (`MaxPooling2D`), achatamento (`Flatten`) e camadas densas com ativações `ReLU` e `Softmax`.
5. **Treino e Checkpoints:** Implementação da técnica `ModelCheckpoint` para salvar a melhor versão do modelo com base no desempenho do conjunto de validação[cite: 5].

---
*Desenvolvido por: Beatriz Cavalcante de Melo*
