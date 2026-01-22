# Projetos de Introdução à Inteligência Artificial - Le CNAM 🇫🇷

Este repositório contém os projetos desenvolvidos durante o curso de **Introdução à Inteligência Artificial** no **Conservatoire National des Arts et Métiers (Le CNAM)**, em Paris, como parte do meu programa de intercâmbio.

Os projetos abrangem áreas fundamentais de Deep Learning e Machine Learning, focando tanto em aprendizagem supervisionada para séries temporais quanto em aprendizagem não supervisionada para visão computacional.

---

## 1. Previsão de Séries Temporais com RNN (Dataset CTA)

Implementação e treino de Redes Neurais Recorrentes (RNN) para prever a procura de passageiros na **CTA (Chicago Transit Authority)**.

### 📋 Destaques do Projeto
* **Engenharia de Features:** Transformação de dados brutos de séries temporais em janelas de entrada para modelos sequenciais.
* **Arquitetura Ideal:** 2 camadas ocultas com **16 neurónios** cada, selecionada após testes para evitar o overfitting e garantir a generalização.
* **Métrica de Sucesso:** Avaliação rigorosa através do Erro Médio Absoluto (MAE).



---

## 2. Aprendizagem Não Supervisionada com Fashion MNIST

Exploração de técnicas de clustering e redução de dimensionalidade aplicadas ao dataset **Fashion MNIST**, visando agrupar automaticamente diferentes categorias de vestuário.

### 📋 Destaques do Projeto
* **Processamento de Imagem:** Normalização e preparação de vetores de 784 dimensões (28x28 píxeis).
* **Redução de Dimensionalidade:** Aplicação de **PCA** e **t-SNE** para visualização de dados e melhoria da eficiência dos algoritmos de agrupamento.
* **Clustering:** Implementação do algoritmo **K-Means**
* **Resultados:** Identificação de padrões estruturais nas imagens, alcançando uma configuração de modelo estável com baixa lacuna de generalização.



---

## 🛠️ Tecnologias e Ferramentas

* **Linguagem:** Python 3.7+
* **Frameworks de ML/DL:** `TensorFlow`, `Keras`, `Scikit-Learn`.
* **Processamento de Dados:** `Pandas`, `NumPy`.
* **Visualização:** `Matplotlib`, `Seaborn`.
* **Ambiente:** Google Colab / VS Code.

## 🚀 Como Executar os Notebooks

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
    ```
2.  Instale as dependências:
    ```bash
    pip install tensorflow scikit-learn pandas numpy matplotlib
    ```
3.  Abra os ficheiros `.ipynb` no seu editor de preferência (VS Code ou Jupyter) para visualizar as análises e resultados.

---
*Desenvolvido como parte do currículo acadêmico no Le CNAM (2025-2026).*
