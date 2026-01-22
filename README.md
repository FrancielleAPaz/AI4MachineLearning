# Previsão de Séries Temporais com RNN (Dataset CTA)

Este projeto consiste na implementação e treino de Redes Neurais Recorrentes (RNN) para a previsão de séries temporais, utilizando dados de passageiros da **CTA (Chicago Transit Authority)**. O objetivo principal é comparar diferentes arquiteturas de modelos e identificar a configuração mais eficiente para prever a procura de transporte.

## 📋 Descrição do Projeto

O projeto aborda o ciclo completo de desenvolvimento de um modelo de Deep Learning:
1.  **Pré-processamento de Dados:** Limpeza, tratamento de duplicados, renomeação de colunas e formatação de séries temporais.
2.  **Engenharia de Features:** Preparação dos dados para entrada em modelos sequenciais.
3.  **Desenvolvimento de Modelos:** Experimentação com múltiplas arquiteturas de RNN utilizando a biblioteca Keras/TensorFlow.
4.  **Avaliação:** Análise de métricas de erro (MAE) e comportamento das curvas de aprendizagem (overfitting vs. generalização).

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3.7+
* **Bibliotecas Principais:**
    * `TensorFlow` / `Keras` (Modelagem Deep Learning)
    * `Pandas` e `NumPy` (Manipulação de dados)
    * `Matplotlib` (Visualização)
    * `Scikit-Learn` (Escalonamento e métricas)

## 🏗️ Arquitetura do Modelo

Após a fase de experimentação, foi determinada a seguinte configuração como a ideal:
* **Tipo:** Rede Neural Recorrente (RNN).
* **Estrutura:** 2 camadas ocultas com **16 neurónios** cada.
* **Justificação:** Embora modelos com mais neurónios (ex: 64) tenham apresentado um MAE ligeiramente inferior, a arquitetura de 16 neurónios foi selecionada por apresentar um melhor equilíbrio, evitando o **overfitting** e mantendo uma complexidade computacional reduzida.

## 📈 Resultados e Observações

* **Métrica de Avaliação:** Erro Médio Absoluto (MAE).
* **Comportamento de Treino:** Foi observado que, em certas iterações, a perda de validação foi inferior à de treino. Isto foi atribuído à mecânica de cálculo do Keras (onde a perda de treino é a média durante a época e a de validação é calculada no final) ou à distribuição favorável dos dados no split de validação.
* **Ajustes Futuros:** Identificou-se a necessidade de ajustar a *learning rate* em iterações posteriores para estabilizar a convergência.

## 🚀 Como Utilizar

1.  Certifica-te de que tens o Python instalado.
2.  Instala as dependências necessárias:
    ```bash
    pip install tensorflow pandas numpy matplotlib scikit-learn
    ```
3.  Executa o notebook `RNN_training.ipynb` num ambiente Jupyter ou Google Colab.
