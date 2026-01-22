# Projetos de Introdução à Inteligência Artificial - Le CNAM 🇫🇷

Este repositório contém os projetos desenvolvidos durante o curso de **Introdução à Inteligência Artificial** no **Conservatoire National des Arts et Métiers (Le CNAM)**, em Paris, como parte do meu programa de intercâmbio.

Os projetos abrangem a área de Artficial Neural Networks, focando tanto em aprendizagem supervisionada para séries temporais quanto em aprendizagem supervisionada para classificação de imagens usando multilayer perceptrons(MLP).

---

## 1. Previsão de Séries Temporais com RNN (Dataset CTA)

Implementação e treino de Redes Neurais Recorrentes (RNN) para prever a procura de passageiros na **CTA (Chicago Transit Authority)**.

### 📋 Destaques do Projeto
* **Engenharia de Features:** Transformação de dados brutos de séries temporais em janelas de entrada para modelos sequenciais.
* **Arquitetura Ideal:** 2 camadas ocultas com **16 neurónios** cada, selecionada após testes para evitar o overfitting e garantir a generalização.
* **Métrica de Sucesso:** Avaliação rigorosa através do Erro Médio Absoluto (MAE).



---

## 2. Classificação de Imagens com MLP (Fashion MNIST)

Desenvolvimento e validação de uma **Multi-Layer Perceptron (MLP)** para a classificação automatizada de artigos de vestuário utilizando o dataset **Fashion MNIST**.

### 📋 Destaques do Projeto
**Busca de Hiperparâmetros:** Implementação de uma estrutura experimental para testar variações na arquitetura da rede (número de camadas e neurónios por camada).
* **Performance:** O modelo final alcançou aproximadamente **88% de acurácia** no conjunto de teste, apresentando um *generalization gap* reduzido (~2%).
* **Visualização:** Uso de Heatmaps para analisar a relação entre a complexidade do modelo e a precisão obtida.



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