
# Estratégia de Hedge Usando Inteligência Artificial

Este projeto foi desenvolvido no contexto do curso **Engenharia Financeira com Inteligência Artificial** da **Data Science Academy**. O objetivo é explorar a aplicação de **modelos matemáticos clássicos** e **técnicas de IA** na construção de estratégias de hedge no mercado financeiro.

## 🎯 Objetivo

O projeto busca implementar e comparar abordagens para precificação e cobertura (hedge) de opções financeiras, unindo métodos tradicionais (como o modelo **Black-Scholes-Merton**) a algoritmos de **redes neurais artificiais**.

## 📂 Estrutura do Projeto

* **Fase 1 - Processamento dos Dados**

  * Simulação de trajetórias do preço de ativos usando **Monte Carlo**.
  * Cálculo do **delta** e precificação de opções via modelo Black-Scholes-Merton (BSM).

* **Fase 2 - Inteligência Artificial Aplicada**

  * Implementação de **redes neurais** com Keras/TensorFlow.
  * Treinamento de modelos preditivos para estimar preços de opções.
  * Comparação entre os resultados obtidos por métodos tradicionais e IA.

## 🛠️ Tecnologias Utilizadas

* **Python 3.x**
* **Bibliotecas principais**:

  * `numpy`, `pandas`, `scipy`
  * `plotly` (visualizações)
  * `tensorflow`, `keras` (modelagem preditiva)
  * `tqdm` (monitoramento de execução)

## 📈 Principais Conceitos

* **Black-Scholes-Merton (BSM):** modelo clássico para precificação de opções.
* **Delta:** sensibilidade do preço da opção em relação ao ativo subjacente.
* **Simulação de Monte Carlo:** técnica estocástica para estimar preços e trajetórias de ativos.
* **Redes Neurais:** aplicadas para prever preços de opções e melhorar a eficiência de estratégias de hedge.

## 🚀 Como Executar

1. Clone este repositório.
2. Instale as dependências necessárias:

   ```bash
   pip install -r requirements.txt
   ```
3. Abra o Jupyter Notebook e execute o arquivo:

   ```bash
   jupyter notebook Projeto9-Fase2.ipynb
   ```

## 📌 Resultados Esperados

* Compreensão da dinâmica de precificação de opções.
* Construção de estratégias de hedge utilizando IA.
* Análise comparativa entre modelos tradicionais e de aprendizado de máquina.
