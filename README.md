# Classificação de Imagens de Histopatologia com Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

## Sobre o Projeto

Este repositório contém o trabalho desenvolvido para a disciplina de **Inteligência Artificial**.

O projeto foca na classificação automática de imagens de histopatologia para a detecção de **Carcinoma Ductal Invasivo (IDC)** em amostras de câncer de mama. O objetivo é comparar o desempenho de diferentes algoritmos de aprendizado supervisionado no processamento e classificação dessas imagens médicas.

## Algoritmos Avaliados

O estudo contempla a aplicação e análise comparativa dos seguintes classificadores:

1. **SVM (Support Vector Machine)**
2. **Random Forest (Floresta Aleatória)**
3. **Logistic Regression (Regressão Logística)**

Para o processamento das imagens, foi utilizada a biblioteca **OpenCV**, incluindo técnicas de redimensionamento e normalização.

## Estrutura do Repositório

```text
histo-class-ia/
  ├── notebook/
  │   └── Breast-Cancer-Classification-IDC.ipynb
  ├── .gitignore
  └── README.md
```

## Instruções de Uso

### 1. Clonagem do Repositório

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
```

### 2. Execução no Google Colab

1. No Google Colab, vá em **Arquivo > Abrir notebook**.
2. Selecione a aba **GitHub** e cole o link do repositório.
3. Instale as dependências necessárias, caso necessário:

```bash
pip install scikit-learn opencv-python seaborn
```

### 3. Base de Dados

Os experimentos utilizam um dataset de imagens histopatológicas para classificação de IDC. Certifique-se de que os caminhos utilizados no notebook estejam compatíveis com a estrutura de diretórios do ambiente de execução.

## Autores

- **Breno Souza Guedes** — Desenvolvedor
