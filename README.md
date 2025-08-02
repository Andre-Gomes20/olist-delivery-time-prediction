# ⏱️ Previsão de Tempo de Entrega - Olist

Este projeto utiliza machine learning para prever o **prazo de entrega de pedidos** de um e-commerce brasileiro (Olist), com base em dados reais de vendas, produtos, clientes e vendedores.

---

## 📦 Sobre o Projeto

O objetivo é criar um modelo de regressão capaz de prever, com boa precisão, o número de dias que um pedido levará para ser entregue ao cliente.

---

## 🔍 Tecnologias Utilizadas

- Python 3.11
- Pandas e NumPy (manipulação de dados)
- Scikit-learn (modelos de ML)
- Jupyter Notebook
- Git e GitHub

---

## 🧠 Modelos Treinados

Foram testados três modelos principais:

| Modelo                 | MAE ↓ | MSE ↓ | R² ↑  |
|------------------------|--------|--------|-------|
| Linear Regression      | 4.63   | 35.17  | 0.15  |
| Gradient Boosting      | 4.17   | 25.87  | 0.38  |
| Random Forest Regressor| ✅ 3.03| ✅ 17.11| ✅ 0.59 |

O melhor desempenho foi obtido com o **Random Forest**, que explicou cerca de **59% da variância** dos dados.

---

## 🗂️ Estrutura de Pastas

```bash
olist-delivery-time-prediction/
│
├── data/                     # Arquivos CSV da Olist
├── notebooks/
│   └── main.ipynb            # Notebook principal do projeto
├── venv/                     # Ambiente virtual (não versionado)
├── README.md                 # Este arquivo
└── requirements.txt          # Bibliotecas usadas no projeto

📬 Contato
Desenvolvido por André
📧 andre.gomes.pro01@gmail.com