# 🏡 House Price Prediction - Machine Learning

Este projeto aplica **Regressão Linear** para prever preços de imóveis, utilizando Python e bibliotecas de análise de dados e estatística.  

O objetivo é entender a relação entre variáveis explicativas (área, número de quartos, banheiros, garagem etc.) e o preço das casas, construindo um modelo interpretável e validado com métricas de desempenho.  

---

## 📂 Estrutura do Projeto
- `data/` → contém o dataset bruto.
- `notebooks/` → Jupyter Notebook com a análise completa.
- `src/` → funções Python para tratamento e modelagem.
- `models/` → modelo salvo em formato `.joblib`.
- `reports/` → imagens e resultados da análise.
- `requirements.txt` → bibliotecas necessárias

---

## 🚀 Passos do Projeto
1. **Carregamento dos Dados**  
   Importação e limpeza da base.  

2. **Análise Exploratória (EDA)**  
   Visualização de distribuições, correlações e insights iniciais.  

3. **Processamento dos dados:**
   Separando dados em treino e teste e teste de multicolinearidade.

4. **Treinamento com OLS (Ordinary Least Squares)**  
   Ajuste do modelo e interpretação dos coeficientes.  

5. **Divisão Treino/Teste**  
   Separação dos dados para avaliação justa.  

6. **Métricas de Avaliação**  
   - MAE (Mean Absolute Error)  
   - RMSE (Root Mean Squared Error)  
   - R² (Coeficiente de determinação)  

7. **Análise de Resíduos**  
   Verificação dos pressupostos do modelo linear.  

---

## 🛠️ Tecnologias Utilizadas
- Python 3.13.7  
- Pandas 2.2.2 
- NumPy 1.26.4
- Matplotlib 3.10.6
- Seaborn 0.13.2
- Statsmodels 0.14.5
- Scikit-learn 1.7.2
- joblib 1.5.2


---

## 📊 Resultados
O modelo conseguiu capturar as principais relações entre os atributos dos imóveis e seus preços, fornecendo previsões interpretáveis e insights para análise.  

---

## ▶️ Como Executar
1. Clone este repositório:  
   ```bash
   git clone https://github.com/JCarapina/Primeiro_regression.git
   ```
2. Abra o notebook `house_price.ipynb` no **Jupyter Notebook** ou **Google Colab**.  
3. Execute célula por célula para reproduzir os resultados.  

---

## 📌 Autor
Projeto desenvolvido por [João Carapina].  
📫 Me encontre no [LinkedIn] https://www.linkedin.com/in/joao-vitor-carapina-barbosa-04084433a/

